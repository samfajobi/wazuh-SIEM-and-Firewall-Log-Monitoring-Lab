## Step 9: Add a Wazuh Agent (Example: Ubuntu Client)

On the **agent machine**:

1. Download agent package:

```bash
curl -sO https://packages.wazuh.com/4.x/apt/wazuh-agent_4.7.0-1_amd64.deb
sudo dpkg -i wazuh-agent_4.7.0-1_amd64.deb
```

2. Configure agent:

```bash
sudo nano /var/ossec/etc/ossec.conf
```

Set manager IP:

```xml
<server>
  <address>192.168.100.20</address>
</server>
```

3. Start agent:

```bash
sudo systemctl enable wazuh-agent
sudo systemctl start wazuh-agent
```

---

## Step 10: Verify Agent Connection

From the **Wazuh Dashboard**:

* Go to **Agents**
* Confirm the agent status is **Active**

---
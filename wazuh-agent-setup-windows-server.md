# Windows Server Enrollment into Wazuh

This document outlines the steps used to **enroll a Windows Server host into Wazuh** as part of a SOC monitoring and detection lab.
The goal is to enable **centralized log collection, endpoint visibility, and security monitoring** from Windows Server into the Wazuh manager.

---

## Prerequisites

Before enrolling the Windows Server, ensure the following:

* Wazuh Manager is installed and running
* Wazuh Dashboard is accessible
* Network connectivity exists between the Windows Server and Wazuh Manager
* Administrator privileges on the Windows Server

---

## Step 1: Create a Wazuh Agent Entry


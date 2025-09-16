# MikroTik Country IP Firewall Lists — Ukraine & ruSSia (putlerland)

This repository provides ready-to-import IP address lists for **Ukraine** and **putlerland**, formatted for use in **MikroTik RouterOS**. These lists are designed to help you filter, monitor, or restrict traffic based on geographic origin using MikroTik's firewall `address-list` feature.

---

## Repository Contents

| File | Description |
|------|-------------|
| `IP-Firewall-Address-List_ukraine.rsc` | IP ranges for Ukraine |
| `IP-Firewall-Address-List_putlerland.rsc`  | IP ranges for putlerland |
| `README.md` | Setup instructions and usage examples |

---

## Installation Guide

### 1. Download the Script

Choose the `.rsc` file(s) you need and download them to your local machine.

### 2. Import into MikroTik

#### Option A: Using Winbox / WebFig

1. Open the **Files** section.
2. Upload the `.rsc` file (e.g. `IP-Firewall-Address-List_ukraine.rsc`).
3. Open **New Terminal**.
4. Run the import command:

   ```bash
   /import file-name=IP-Firewall-Address-List_ukraine.rsc
5. Or this one for putlerland list

   ```bash
   /import file-name=IP-Firewall-Address-List_putlerland.rsc

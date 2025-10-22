# VMware Tools Tutorial (Parrot OS Example)

## 1. Prerequisites

* VMware Workstation Pro installed on your host
* A Linux guest OS (e.g., Parrot OS) running in a VM
* Internet connection (for installing packages)

---

## 2. Install VMware Tools in Parrot OS

1. Boot your Parrot OS VM.
2. Open a terminal and update the system:

   ```bash
   sudo apt update && sudo apt upgrade -y
   ```
3. Install the VMware integration packages:

   ```bash
   sudo apt install open-vm-tools open-vm-tools-desktop -y
   ```
↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓
👉 [Read the full tutorial](https://github.com/tudes00/ZeroLab/blob/main/notes/tuto/VMware/Vmware-Tools.m)

This tutorial and many others are available entirely on [zerolab](https://github.com/tudes00/ZeroLab/)
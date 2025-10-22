# Install DVWA on ParrotOS, Kali linux, or any other Debian-based distro

[DVWA](https://github.com/digininja/DVWA) is a vulnerable web application that is used for security training. It is designed to be an aid for security professionals to test their skills and tools in a legal environment.

---

## Prerequisites

- **ParrotOS or other Debian-based distro** installed on your system (If you don't, check [this tutorial](../VMware/Install-Parrot-Security-OS-VMware.md) first).
- Basic knowledge of using the terminal and Linux commands.

---

## Table of contents

* [Download Parrot ISO](#download-parrot-iso)

---

## Download DVWA
1. Open a terminal in ParrotOS.
2. Navigate to the web server directory:
   ```bash
   cd /var/www/html
   ```
3. Clone the DVWA repository from GitHub:
   ```bash
    sudo git clone https://github.com/digininja/DVWA.git
    ```
4. Change the permissions of the DVWA directory:
   ```bash
   sudo chmod -R 777 DVWA
   ```
↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓
👉 [Read the full tutorial](https://github.com/tudes00/ZeroLab/blob/main/notes/tuto/linux/Install-DVWA.md)

This tutorial and many others are available entirely on [zerolab](https://github.com/tudes00/ZeroLab/)
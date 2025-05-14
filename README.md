# Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

# NAME: Kamali E
# REG NO:212222110015

# Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

# 3.a) Installation and Configuration of Oracle VirtualBox

# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access Minimum 4 GB RAM Sufficient storage space

# Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site Download installer for your OS (Windows/macOS/Linux). Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next. Choose Installation Options → Click Next. Accept Network Interface Warning → Click Yes. Click Install. Finish Installation and Launch VirtualBox. Configure VirtualBox:

Open VirtualBox. Click New → Name VM → Select Type (Linux/Windows) and Version. Allocate: Minimum 2 GB RAM Create Virtual Hard Disk (20 GB recommended). Start Virtual Machine and provide ISO to install OS. Result: Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux

# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
Oracle VM VirtualBox Installed 4 GB RAM and 20 GB Storage Minimum Kali Linux ISO image

# Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site Download 64-bit ISO (Installer version). Create a New Virtual Machine:

Open VirtualBox → Click New. Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit). Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB). Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image). Choose Dynamically allocated. Set Disk size to 20 GB or more. Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO. Start Installation:

Boot Virtual Machine → Choose Graphical Install. Set Language, Region, Keyboard. Configure Network → Set Hostname (e.g., kali). Set root password. Disk Partitioning: Use entire disk → All files in one partition. Install System → Install GRUB Bootloader → Finish Installation. Login to Kali Linux:

Use root credentials. (Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

# Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

![image](https://github.com/user-attachments/assets/ad8f10e0-8324-4ee4-b984-1f626e44b686)

Snapshot 2: Kali Running in Virtual

![image](https://github.com/user-attachments/assets/c9a71414-0371-4f66-a7b6-1d2b6a997696)

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system. Kernel manages communication between hardware and software. Commands are case-sensitive.

# Linux Commands:
ls Command The ls command is used to display a list of content of a directory.

Syntax:ls

![image](https://github.com/user-attachments/assets/e79a843a-7738-4da9-9df8-3fb93c38a7c4)

# pwd Command 
The pwd command is used to display the location of the current working directory.
Syntax:
pwd

![image](https://github.com/user-attachments/assets/5fc95228-2ec4-453c-9500-23df414bd847)

![image](https://github.com/user-attachments/assets/56f5e9e3-3047-4e65-9352-705e8b0e688c)

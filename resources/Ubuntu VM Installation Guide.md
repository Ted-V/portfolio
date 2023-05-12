# How to Install Ubuntu Linux on a Virtual Machine Using VirtualBox
#  About this guide
This guide explains how to use Oracle's VirtualBox software to install linux on a virtual machine. You may use this guide to install other linux distributions but note that system requirements may vary. This guide features Windows as the host operating system and Ubuntu as the linux distribution of choice. 

<!-- ## Terms
**Virtual machine** - a computer emulation that runs inside your physical machine. 

**Ubuntu linux** - a popular Linux-based operating system.

**VirtualBox** - a free, open-source tool for virtualizing x86 computing architecture. -->

<!-- ## Use
Practical uses for virtual machines include:
- Trying a new operating system
- Running outdated software
- Developing software
- Handling potential malware
- Cloning a system to another machine
- Practicing computer networking skills -->

# Prerequisites
Hardware requirements for Ubuntu
- 2 GHz dual-core processor or better 
- 4 GB RAM
- 25 GB of free hard drive space

# Instructions

## Step 1: Download VirtualBox

[Click here](https://www.virtualbox.org/wiki/Downloads) and download VirtualBox for your current operating system.

![Step 1](imgs/downloadwindowshosts.png)

## Step 2: Download Ubuntu ISO

[Click here](https://ubuntu.com/download/desktop) and download the latest version of Ubuntu. This guide features Ubuntu version 22.04.2 LTS.

<!-- ![Step 2](imgs/Step%20%202%20-%20Download%20Ubuntu.png) -->

## Step 3: Install VirtualBox

1. Navigate to your downloads and launch VirtualBox's set up application.

2. Follow the application to install VirtualBox. Keep all settings default unless you desire otherwise.

## Step 4: Create a New Virtual Machine

1. Launch VirtualBox.

2. Click **New**.

![Step 4.2](imgs/launchvbox.png)  

## Step 5: Identify Your New Virtual Machine

![VM Set up](imgs/name%20virtual%20machine%20and%20operating%20system.png)  

1. Enter a name for the virtual machine.   

2. Enter a destination folder for the virtual machine.  

3. Select the Ubuntu ISO you previously downloaded.  

4. Leave **Skip Unattended Installation** unselected.  

5. Click **Next**.  

## Step 6:  Configure the Guest OS Installation  

![Unattended Guest OS Installation Screenshot](imgs/unattended%20guest%20os%20install%20setup.png)  

1. Enter a username and password. The default password is `changeme`.  

2. Select **Guest Additions**.  

3. Select **Install in Background**.  

4. Leave **Hostname**, **Domain Name**, and **Guest Additions ISO** as they are.  

5. Click **Next**.  

## Step 7: Allocate Your Computer's Resources

![VM hardware configuration](imgs/hardware.png)  

1. Select how much working memory to allocate to your virtual machine. We recommend at least 2048 MB. The green upper limit is equal to half of your total RAM.

2. Select how many processors to allocate to your virtual machine. We recommend selecting **2**.

3. Leave **Enable EFI** unselected.

4. Click **Next**.

**Note: You can adjust these values later in VirtualBox's VM Settings menu.**

## Step 8: Adding a Virtual Hard Disk

![VM Hard Disk Creation](imgs/virtual%20hard%20disk.png)

1. Select **Create a Virtual Hard Disk** and select the amount of storage memory you want to allocate to your virtual machine. We recommend selecting 30 GB.

2. Click **Next**.

3. Review your installation summary and click **Finish**.

## Step 9: Installing Ubuntu

1. Navigate to the VirtualBox Manager window.

![Show live VM](imgs/installedubuntu.png)

1. Click **Show**. Your new virtual machine should be running in a separate window.

2. Create your Ubuntu log-in credentials and click **Continue**.

![Alt text](imgs/linuxinstall.png)

4. Await installation. If the installation was successful, you should see a welcome screen like the one below. 

![Welcome to Ubuntu ScreenCap](imgs/welcomeubuntu.png)

Your new virtual machine is now set up and ready to use. 
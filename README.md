# kali-linux-virtual-box
<h1>Step by step guide on kali linux virtual machine</h1> 
Installing-Kali-on-virtual-box
In this guide, I’ll walk you through the process of downloading and installing Kali Linux on VirtualBox. Kali Linux is a powerful penetration testing platform, and setting it up virtually allows you to practice ethical hacking and cybersecurity safely. Let’s get started with the step-by-step instructions!

<h2>Step 1: Download Kali Linux ISO</h2>
<a href="https://www.kali.org/get-kali/#kali-installer-images">Click here</a> to Visit the Official Kali and download the latest version of Kali Linux ISO suitable for your system (32-bit or 64-bit). Generally, you'll want the 64-bit version if your system supports.



Extract the downloaded file using a reliable extraction tool like WinRAR or 7-Zip. Ensure the files are extracted to a designated folder for easy access during the installation process.



<h2>Step 2: Create a New Virtual Machine</h2>
By now, you should have VirtualBox downloaded and installed. If not, check out my guide linked here for assistance. Open VirtualBox, then click on the "New" button to proceed.



Name and Operating System
Name your virtual machine (e.g., "Kali Linux"), choose "Linux" as the Type, and select "Ubuntu (64-bit)" as the Version if using the 64-bit ISO.



<h2>Step 2 con’t: Memory Size</h2>
Allocate a minimum of 4096 MB of memory for your virtual machine; however, 8192 MB (8 GB) or more is recommended for better performance. For the processor, assign at least 4 CPUs if available.



<h2>Step 3: Create a Virtual Hard Disk</h2>
Allocate at least 20 GB of storage for Kali Linux, though you can choose a larger size if you have sufficient disk space.



<h2>Step 4: Configure VM Settings</h2>
Choose your virtual machine and click "Settings." Navigate to the "Storage" section, then click the empty CD icon under "Controller: IDE." Next, select "Choose a disk file..." and locate the Kali Linux ISO file you previously downloaded. This process attaches the ISO to your virtual machine for installation.



<h2>Step 5: Configure the Network</h2>
Make sure your network settings are properly configured. It is recommended to use the Bridged Adapter setting, which allows your virtual machine to function as a separate device on your physical network. The VM will receive its own unique IP address either dynamically from the network’s DHCP server or through manual static configuration. This setup enables the virtual machine to interact seamlessly with other devices on your network, just like a physical computer. The Bridged Adapter option ensures better connectivity and access to network resources, making it ideal for scenarios that require full network integration for testing or communication purposes.



<h2>Step 6:Start the VM</h2>
Click "Start" to boot the VM. Once booted, log in using the default credentials: Username: "kali" and Password: "kali".





<h2>Step 7: Update Kali</h2>
Launch a terminal and execute the command: sudo apt update to ensure your system's package list is updated with the latest repositories.



Once the update is complete, run the command sudo apt upgrade -y to upgrade your Linux system to the latest available packages and enhancements.



<h2>Note</h2>
Download the Correct ISO: Ensure you download the appropriate 64-bit or 32-bit ISO file from the official Kali Linux website.

Virtualization Software: Install VirtualBox or VMware for a virtual setup.

Allocate Resources: Provide sufficient RAM (4GB or more) and disk space (20GB minimum).

Network Settings: Use Bridged Adapter for seamless network connectivity.

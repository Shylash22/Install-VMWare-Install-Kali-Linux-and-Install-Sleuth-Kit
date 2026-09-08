# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: Mahith M
### Reg No: 212225240082
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.
@@ -44,14 +44,17 @@ To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Ki

### Design Steps:
## Step 1: Install VirtualBox
Installation Steps:
Download the Windows hosts .exe file from the official VirtualBox website.
Run the installer and follow the on-screen instructions.
Once installed, launch VirtualBox to verify the installation.
## Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

##  Installation Steps:
Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
Go to Settings > Storage, click Empty under Controller: IDE.
Select Graphical Install, follow the prompts to set language, location, username, and password.
Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.
## Step 3: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

## Installation Steps:
Download the Windows ZIP package from the official website.
Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
Add the bin folder to Windows PATH:
Open Control Panel → System → Advanced System Settings.
Click Environment Variables → Edit Path.
Add the Sleuth Kit bin folder path and save changes.
Verify installation by running:
fls -version

## OUTPUT:
**VIRTUAL BOX:**
<img width="1315" height="702" alt="435592141-e678fe11-ad1b-46b6-b7f1-7c8c659d04c3" src="https://github.com/user-attachments/assets/bb8b17a4-2693-49c7-933f-a4168a28506c" />


**KALI LINUX:**

<img width="1913" height="942" alt="image" src="https://github.com/user-attachments/assets/a4e98d18-21d1-4289-99fc-01ebe09e381c" />


**SLEUTH-KIT:**

<img width="1473" height="735" alt="433664257-1644ac29-a76a-4e74-b3c5-7b8874824322" src="https://github.com/user-attachments/assets/c97f4d96-c8f8-4782-965e-2418f3aef3dc" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.

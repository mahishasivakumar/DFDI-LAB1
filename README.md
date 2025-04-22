# EXP1: INSTALL VMWARE, INSTALL KALI LINUX AND INSTALL SLEUTH KIT. 
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

```
Register Number: 212222040095
Name: Mahisha S
```

## EQUIPMENT REQUIRED:
  ●	Hardware: Personal Computer (PC)


## DESIGN STEPS:

### Step 1:

Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

### Step 2:

Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

### Step 3:

Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

## INSTALLATION PROCEDURE:
INSTALLING VMWARE:
### Step 1. Download VirtualBox
  •	Go to: https://www.virtualbox.org/
  
  •	Click on the “Downloads” link in the left menu
  
  •	Under VirtualBox x.x.x platform packages, click Windows hosts
  ![Screenshot 2025-04-22 185911](https://github.com/user-attachments/assets/1bec80de-b48c-4695-8e97-c57e2af3c6c0)


### Step 2. Run the Installer
  •	Locate the downloaded .exe file (usually in your Downloads folder)
  ![Screenshot 2025-04-22 190227](https://github.com/user-attachments/assets/7b508958-3d14-4a39-aba3-d82e7995e196)

  
  •	Double-click it to run the installer
### Step 3. Installer Wizard
![Screenshot 2025-04-22 190511](https://github.com/user-attachments/assets/f386a1f7-9d15-4db6-9c30-73a05d401f61)


  •	Click Next
  
  •	Keep default settings unless you want to change install location or features
  
  •	Click Next
### Step  4. Network Interface Warning
  •	Click Yes to proceed (this may temporarily disconnect your internet)
  !![Screenshot 2025-04-22 190536](https://github.com/user-attachments/assets/85560961-c92b-46f2-ac1c-517451b051ff)


### Step  5. Begin Installation
  •	Click Install
  ![Screenshot 2025-04-22 190558](https://github.com/user-attachments/assets/3c2009d4-1b94-42bb-a202-96574db13916)

  
  •	If asked for permission by User Account Control (UAC), click Yes

## OUTPUT:
  •	Click Finish
  
  •	VirtualBox will launch (if the checkbox is ticked)
  ![Screenshot 2025-04-22 190656](https://github.com/user-attachments/assets/93b8da88-0549-4147-ae37-d5d6ad55b5f6)


## INSTALLING KALI LINUX:
### Step 1: Open Oracle VirtualBox
  •	After installing VirtualBox, open it.
  
  •	The main screen of VirtualBox should appear.
### Step 2: Download Kali Linux VirtualBox Image
  •	Go to:
   https://cdimage.kali.org/kali-2024.4/kali-linux-2024.4-virtualbox-amd64.7z
   
  •	Download the .7z file (Kali Linux VirtualBox image)
  ![image](https://github.com/user-attachments/assets/0ca20847-91fe-4745-b21e-ac4d0caa72a4)
  
### Step 3: Extract the File
  •	Use 7-Zip or WinRAR to extract the .7z file:
  
  o	Right-click on the downloaded file
  
  o	Select "Extract Here" or "Extract to Folder"
  
  •	You’ll get a folder containing a .vbox file (VirtualBox Machine Definition File)
### Step 4: Import Kali Linux into VirtualBox
  •	Open VirtualBox
  
  •	Click on File → Import Appliance
  ![Screenshot 2025-04-22 190821](https://github.com/user-attachments/assets/3806cbd6-444f-436c-8e66-61f6fe2f8417)

  
  •	Click Choose, then browse to the extracted .vbox file
  
  •	Select the .vbox file and click Next
  
  •	Keep the default settings as they are
  
  •	Click Import  Wait for the import process to complete
### Step 5: Start Kali Linux
  •	Once imported, you will see "Kali Linux" in the left panel
  
  •	Select it and click Start and the Kali Linux will boot up
  ![Screenshot 2025-04-22 190859](https://github.com/user-attachments/assets/b543e306-5ab1-4dd5-ab6a-92c301550ee9)

  ![Screenshot 2025-04-22 190937](https://github.com/user-attachments/assets/e8630e49-b95f-4df2-a9ab-da74506ce9bd)

  ![Screenshot 2025-04-22 190954](https://github.com/user-attachments/assets/b46f063d-a3b4-4a10-8a1c-958c9a4b3c53)

  
## OUTPUT:
  •	After login (default username: kali, password: kali)
  
  •	Open the Terminal (black monitor icon)
  
  •	Try the basic Linux commands:
  ![Screenshot 2025-04-22 191013](https://github.com/user-attachments/assets/78f60758-825e-4ce3-b890-f25623a2c27c)

  
## INSTALLING SLEUTH KIT:
  •	Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php
  ![image](https://github.com/user-attachments/assets/9355a68d-e06d-4642-971b-8cda41f6229e)
  
  ●	Move the downloaded folder to the program files.
  
  ●	Go to the system environment variables.
  ![image](https://github.com/user-attachments/assets/cd11b600-7248-4db7-9056-103cd0375274)
  ![image](https://github.com/user-attachments/assets/9b23a2db-287e-45e0-8037-5abdadccc401)
  
  ● Click environment variables.
  ![image](https://github.com/user-attachments/assets/63bf5230-4ef6-457c-b084-7012086de8e4)
  ![image](https://github.com/user-attachments/assets/7b371029-5ce9-4050-8252-26901ab81b4e)
  
  ●	Click the path
  
  ●	Now add the sleuth kit folder address.
  
  ●	And the click ok. USING OF SLEUTH KIT:
  ![image](https://github.com/user-attachments/assets/c8ec3ab7-646e-4f93-a02a-54a2698f05fa)
  
## OUTPUT:
  ● Open command prompt and type fls -V to check sleuth kit is installed or not.
  
  ●	Lists partition layout
  ![image](https://github.com/user-attachments/assets/13fd54bd-3807-48b9-a923-25e85f1a9735)
  
  ●	Lists files and directories
  ![image](https://github.com/user-attachments/assets/968d265d-8065-47a3-9e38-2f4032bb2535)

These are the some of the commands used in the Sleuth kit.

## RESULT:
Thus the vmware, kali linux and sleuth kit has been installed successfully.


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
  ![image](https://github.com/user-attachments/assets/68c57786-55e8-4e56-a439-2f119a722edb)

  
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
  ![Screenshot 2025-04-22 201258](https://github.com/user-attachments/assets/9c1e7495-36c2-4fd0-8944-3b7435f69391)

  ![Screenshot 2025-04-22 201341](https://github.com/user-attachments/assets/965d4ea2-2640-451c-98e9-6b7d5293b261)

  
  ● Click environment variables.
  ![Screenshot 2025-04-22 201402](https://github.com/user-attachments/assets/28cf0049-90c1-4e13-8a88-0b9a7ca8390b)

  ![Screenshot 2025-04-22 201452](https://github.com/user-attachments/assets/af5d68c6-fd6a-4799-ad77-810944b3a2ec)

  
  ●	Click the path
  
  ●	Now add the sleuth kit folder address.
  
  ●	And the click ok. USING OF SLEUTH KIT:
  ![Screenshot 2025-04-22 201546](https://github.com/user-attachments/assets/482f4809-1677-42ec-8cf2-34e48af83e20)

  
## OUTPUT:
  ● Open command prompt and type fls -V to check sleuth kit is installed or not.
  
  ●	Lists partition layout
  ![Screenshot 2025-04-22 201607](https://github.com/user-attachments/assets/aec6b61a-df7a-4f53-bb29-1c6e2fa7dc02)

  
  ●	Lists files and directories
  ![Screenshot 2025-04-22 201639](https://github.com/user-attachments/assets/9b53b1a3-3891-485b-b495-9f2f7bbe8f41)


These are the some of the commands used in the Sleuth kit.

## RESULT:
Thus the vmware, kali linux and sleuth kit has been installed successfully.


![image](https://i.imgur.com/qUcz7pD.png)

# Microsoft Azure Virtual Machine Setup Guide

## Introduction
This guide will walk you through the process of creating a virtual machine on Microsoft Azure. By following these step-by-step instructions, you'll have your virtual machine up and running in no time!

### Prerequisites
- An active Microsoft Azure account
- A Microsoft Azure Subscription

## Step 1: Sign in to Azure Portal
1. Open your browser and navigate to [Azure Portal](https://portal.azure.com).
2. Enter your email address and password to sign in.
<img src="https://i.imgur.com/ExNiOVz.png"/>

## Step 2: Create Resource Groups
1. Click on any of the "Resource Groups" on the homepage of Microsft Azure.
2. On the Resource groups page: Click on "Create" or "Create Resource Group" to start.
<table>
<tr>
<td>
<img src="https://i.imgur.com/8EI37a6.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/675FWTh.png" alt="Disk Sanitization Steps" width="100%"/>
</td>
</tr>
</table>

### 2.1 Provide Basic Information for the Basics page
1. Select the appropriate 'Subscription.'
2. Enter a name for your Resource Group. For this example: we will name it Azure-Lab-1.
3. Choose a region closest to your location. For this example: We will select "(US) North Central US".
<img src="https://i.imgur.com/J4aqr2K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### 2.2 Provide Basic Information for the Tags page (Optional)
You have the option to specify a tag if you want. It is used in an organization to keep track of certain data about certain resources or metadata to easily see who created the resource group(s). For this example: We will skip this page.
<img src="https://i.imgur.com/dPInbYP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### 2.3 Review & Create a Resource Group
1. Once it starts validating the information to see if everything is clear, you will see "Validation Passed" in green across the screen. Then you can proceed to create the resource group.
2. The Resource Group is now created.
<table>
<tr>
<td>
<img src="https://i.imgur.com/9zvrdzQ.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/DZiwlcD.png" alt="Disk Sanitization Steps" width="100%"/>
</td>
</tr>
</table>

## Step 3: Create Azure Virtual Machine
1. Select "Azure Virtual Machine".
<img src="https://i.imgur.com/0TPmNH6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### 3.1 Provide Basic Information for the Basics page
## Project details 
1. Select the appropriate 'Subscription.'
2. Create or select an existing 'Resource Group.'
## Instance details
3. Enter a name for your virtual machine. For this example: We will name it "VM1".
4. Choose a region closest to your location. For this example: We will select "(US) North Central US".
5. Choose the Virtual Machine Image. For the example: We will select "Windows 10 Pro, version 22H2 - x64 Gen2".
6.  Select the desired 'Size' for your virtual machine. For the example: We will select "Standard_E2s_v3 - 2 vcpus, 16 GiB memory ($91.98/month)".
## Administrator account
7. Create "Username, Password, then confirm password".
## Licensing
8. Scroll down and check the box that says "I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights" before you click on "Next: Disks".
<table>
<tr>
<td>
<img src="https://i.imgur.com/2Whx8Eu.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/x0pvnVE.png" alt="Disk Sanitization Steps" width="100%"/>
</td>
</tr>
</table>

### 3.2 Provide Basic Information for the Disks page
1. Leave as is.
<img src="https://i.imgur.com/dH02jbP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### 3.3 Provide Basic Information for the Networking page

<table>
<tr>
<td>
<img src="https://i.imgur.com/2Whx8Eu.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/x0pvnVE.png" alt="Disk Sanitization Steps" width="100%"/>
</td>
</tr>
</table>

## Step 4: Configure Settings
### 4.1 Authentication
Choose either 'Password' or 'SSH public key' for authentication.
### 4.2 Inbound Ports
Select necessary ports such as HTTP, HTTPS, or SSH.
### 4.3 Disks
Select the type and size of disks as required.
![Settings]<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

## Step 5: Review and Create
1. Review your virtual machine configuration to ensure everything is correct.
2. Click 'Create' to initiate the deployment.
![Review and Create]<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

## Step 6: Connect to the Virtual Machine
1. Go to the 'Virtual Machines' page.
2. Click on your virtual machine's name.
3. Click the 'Connect' button and follow the instructions to connect via RDP or SSH.
![Connect]<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

## Conclusion
Congratulations! You have successfully created and connected to a virtual machine on Microsoft Azure. If you encounter any issues, refer to the [Azure Virtual Machines documentation](https://docs.microsoft.com/en-us/azure/virtual-machines/).
![Congratulations]<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Enjoy your Azure Virtual Machine, and don't hesitate to reach out with any questions or contributions!

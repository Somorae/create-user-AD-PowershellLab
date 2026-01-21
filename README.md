# 👤 Active Directory User Creation Using PowerShell

## 🎬 Watch Me Build This Lab!
https://www.loom.com/share/d7f98a6f2bc243798183aff42a4f1524

## 🎯 Objective
This lab documents the process of creating a new user account in **Active Directory** using **PowerShell scripts**. The goal is to demonstrate how automation can streamline user provisioning and reduce manual administrative tasks in a Windows domain environment.

## 🛠️ Tools Used
- **Windows PowerShell**
- **Active Directory Users and Computers (ADUC)**
- **AWS Virtual Machine (Windows)**
- **Windows Server / Domain Environment**
- **Notepad (script editing)**

## 🧩 Lab Steps

### 💻 Environment Setup
- Log into your virtual machine hosted on AWS.
- Navigate to **This PC** and open the **Windows (C:) drive**.
- Right-click → **New** → **Folder**.
- Name the folder **`Scripts`**.
- Open the **Scripts** folder (it should be empty).

### 📄 Script Creation
- Right-click inside the folder → **New** → **Text Document**.
- Name the file **Create Active Directory User** and press **Enter**.
- Open the file in **Notepad**.
- Paste your PowerShell script into the document.
- Click **File → Save As**.
- Ensure the file name ends with **`.ps1`**  
  (e.g., `Create Active Directory User.ps1`).
- Save the file in the **Scripts** folder.

### ⚙️ Active Directory Configuration
- Use the Windows search bar and type **Active Directory**.
- Select **Active Directory Users and Computers** from the results.

### ▶️ Script Execution
- Open **Windows PowerShell** from the Start menu.
- Copy the PowerShell script you saved earlier.
- Modify the first four parameters in the script to match the new user’s details.
- Paste the updated script into the PowerShell window.
- Press **Enter** to execute the script.
- Minimize PowerShell after execution.

### 🔍 User Verification
- If the new user does not appear immediately, close and reopen **Active Directory Users and Computers**.
- Search for the newly created user (e.g., *John Doe*).
- Verify that the user account appears successfully.


## ✅ Outcome
- Successfully created a new Active Directory user using PowerShell.
- Verified user creation within Active Directory Users and Computers.
- Demonstrated automation of a common IAM and help desk task.
- Reduced manual user provisioning steps.
- Gained hands-on experience with PowerShell scripting and Active Directory administration.

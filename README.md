# 📥 Microsoft Office 2021 Installation Guide for Students

This repository provides a **clear, simple, and beginner-friendly** guide to install  
**Microsoft Office LTSC Professional Plus 2021** using official Microsoft tools.

✔ Easy to understand  
✔ Step-by-step  
✔ Perfect for students & beginners  

---

## 🧰 Requirements

Before starting, make sure you have:
- A Windows PC
- Stable internet connection
- Administrator access

---

## 🛠 Tools Used

- **Office Customization Tool (OCT)** – to create the Office configuration file  
- **Office Deployment Tool (ODT)** – to download and install Microsoft Office  

---

## 📝 Step 1: Create Office Configuration File

1. Open **Office Customization Tool (OCT)** in your web browser.
2. Configure the settings as follows:

### ✔ Architecture
- Choose **64-bit** (Recommended) or **32-bit**

### ✔ Office Suite
- **Office LTSC Professional Plus 2021 – Volume License**

### ✔ Applications to Install
- Word  
- Excel  
- PowerPoint  
- Access  

### ✔ Language Settings
- English (United Kingdom)  
- English (United States)

### ✔ Installation Options
- **Uninstall MSI versions** → OFF

### ✔ Export Settings
- Select **Office Open XML formats**
- Tick **I accept the terms in the license agreement**
- Click **Export**

📄 A file named **`configuration.xml`** will be downloaded.

---

## 📝 Step 2: Download Office Deployment Tool (ODT)

1. Visit Microsoft’s official website.
2. Download the **Office Deployment Tool**.
3. Save the file on your computer.

---

## 📝 Step 3: Prepare Installation Folder

1. Create a new folder and name it:

```

Office_2021

```

2. Move the following files into this folder:
- `configuration.xml`
- `officedeploymenttool.exe`

3. Right-click **`officedeploymenttool.exe`**  
   → Select **Run as Administrator**

4. Accept the license agreement.
5. Choose the **Office_2021** folder when prompted.  
   The setup files will extract automatically.

---

## 📝 Step 4: Move Folder to Local Disk (C:)

1. Copy the **Office_2021** folder.
2. Paste it inside:

```

C:\

```

✔ Final path:

```

C:\Office_2021

````

---

## 📝 Step 5: Install Microsoft Office Using CMD

1. Open **Command Prompt** as **Administrator**.
2. Navigate to the Office folder:

```cmd
cd C:\Office_2021
````

3. Start the installation:

```cmd
setup /configure configuration.xml
```

⏳ Installation will begin automatically.
Please wait until the process completes.

---

## 🎉 Installation Completed Successfully!

Microsoft Office LTSC Professional Plus 2021 is now installed on your system.

You can now use:

* Microsoft Word
* Microsoft Excel
* Microsoft PowerPoint
* Microsoft Access

---

## 📌 Important Notes

* Always run Command Prompt as **Administrator**
* Do not close CMD during installation
* Internet connection is required during setup

---

⭐ If this guide helped you, please consider giving this repository a **star**!

```
```

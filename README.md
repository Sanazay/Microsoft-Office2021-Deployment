# 📥 Microsoft Office 2021 Deployment (Free Volume License Version)

This repository provides a clean, step-by-step guide to download, configure, and install **Microsoft Office LTSC Professional Plus 2021** using the **Office Customization Tool (OCT)** and **Office Deployment Tool (ODT)**.

---

## 📝 1. Create Office Configuration (Office Customization Tool)

Open the **Office Customization Tool** and configure the following:

### ✔ Architecture
- 32-bit or 64-bit

### ✔ Office Suite
- **Office LTSC Professional Plus 2021 – Volume License**

### ✔ Apps to Install
- Access  
- Word  
- Excel  
- PowerPoint  

### ✔ Languages
- English (United Kingdom)  
- English (United States)

### ✔ Installation Option
- Uninstall MSI versions → **OFF**

### ✔ Export
- Select **Office Open XML formats**
- Tick **I accept the terms in the license agreement**
- Export → saves `configuration.xml`

---

## 📝 2. Download Office Deployment Tool (ODT)

Download the **Office Deployment Tool** from Microsoft's official site.

---

## 📝 3. Prepare Installation Folder

1. Create a new folder:

```

Office_2021

```

2. Move these files inside:
- `configuration.xml`
- `officedeploymenttool.exe`

3. Run `officedeploymenttool.exe` as **Administrator**:
- Accept → Continue
- Choose the **Office_2021** folder
- Files extract automatically

---

## 📝 4. Move Folder to Local Disk (C:)

Copy `Office_2021` → Paste inside:

```

C:\

````

---

## 📝 5. Install Office Using CMD

Open **Command Prompt as Administrator** and run:

```cmd
cd C:\Office_2021
````

Then install Office:

```cmd
setup /configure configuration.xml
```

Office installation will begin automatically ✔

---

## 🎉 Done!

Your Office LTSC Professional Plus 2021 is now installed successfully.

If you want a **sample configuration.xml**, **folder structure**, or **ZIP package**, just ask!

```

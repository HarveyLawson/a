# 🛡️ Malware Detection Guide

## 📌 Overview

Cyber threats can often come from files or programs downloaded from the internet.  
In many cases, it is not possible to determine whether a file is malicious through simple inspection.

### ✅ What this tool does

The Malware Detection feature helps mitigate these risks by:

- Allowing users to upload and scan individual files for malware, viruses, or suspicious activity  
- Providing a continuous folder monitoring system that automatically scans files at set intervals  
- Enabling background scanning of commonly used directories (e.g. Downloads folder)  

---

## 🧭 Accessing the Malware Detection Page

Navigate to **"Malware Detection"** from the left sidebar in the application.

---

## 📄 Single File Scan

At the top of the page, you will see system statistics followed by the **Single File Scan** section.

![Single File Scan Section](./images/single-file-scan.png)

### 🔍 Steps

1. Click inside the upload area (grey box), or drag and drop a file from your computer

![Upload File](./images/upload.png)
   
3. A confirmation message will appear once the file has been uploaded

![File Upload Confirmation](./images/upload-conf.png)

5. Click **"Scan File"** to begin analysis  
6. The scan result will be displayed immediately below  

![Scan Result Example](./images/single-file-result.png)

---

## 📁 Folder Monitoring

The Folder Monitor allows continuous scanning of a selected directory.

---

### 🖥️ Local Usage

If running the application locally:

1. Enter a folder path into the input field  
   Example:

   C:\Users\user\Downloads\

   
![Local Path Example](./images/local-path.png)

---

### 🌐 Demo Environment

If using the hosted demo (e.g. `demo.heml.cc`):

- Local file paths will **not work**
- Use the following demo directory instead:

   /downloads

This folder is pre-filled with files for demonstration purposes.
**If there are no results from /downloads please reset to default and try again!**

![Demo Path Example](./images/demo-path.png)

---

### ⚙️ Configuration Options

- **Scan Interval**  
  Set how frequently the folder is scanned  

- **Scan subfolders recursively**  
  When enabled, all subfolders will also be scanned  

---

## ▶️ Start Monitoring

1. Configure your folder and scan settings  
2. Click the green **"Start Monitoring"** button  

Once started:
- The system will begin scanning immediately  
- If files are present in the folder, results will appear in the table below  

![Monitoring Results](./images/monitoring-results2.png)
---

## ✅ Expected Outcome

- Files will be scanned automatically based on your interval  
- Results will indicate whether files are safe or potentially malicious  
- New files added to the folder will also be detected and scanned  

---

> ⚠️ **Important:**  
> Folder monitoring works best when the application is running locally with access to your file system.



## 🚨 Events and Actions

At the bottom of the Malware Detection page, all detected malware events are displayed in a table with summary details and threat severity.

![Events Table](./images/1.png)

---

### 🔍 Viewing Event Details

Each event includes two actions:

- **View**
- **Acknowledge**

Click **"View"** to open a detailed panel with more information about the detected threat.

![Event Details Panel](./images/2.png)

---

### ⚙️ Available Actions

After reviewing the event details, the following options are available:

![Event Actions](./images/3.png)

- **Delete File**  
  Immediately deletes the malicious file.  
  > ✅ **Recommended action**

- **Acknowledge**  
  Marks the event as reviewed for later action.

- **Restore File**  
  Restores the file from quarantine to its original location.  
  > ⚠️ **Not recommended** — a warning will be shown before proceeding.

---

### ✅ Event Resolution

Once a file is either deleted or restored, the event status will update to:

**Resolved**

![Resolved Event](./images/5.png)

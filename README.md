# 📂 Sync New Files From Google Drive with Airtable
## 📄 Template Description
This automation workflow, designed by **WeblineIndia**, **automatically fetches newly uploaded files** from a specific folder in **Google Drive**, **shares them via email** with designated recipients, and **logs the file details in Airtable** for easy tracking.

It streamlines the entire process of file sharing and management while keeping all important file metadata centralized.

---

## ✅ Workflow Steps

### 1. Google Drive Node - Fetch New File
- **What It Does:** Detects and fetches newly uploaded files from a specific Google Drive folder.
- **How to Set It Up:**
  - Set the **Folder ID** of the desired Google Drive folder.
  - Use the **"New File in Folder"** trigger to monitor the folder.
  - Automatically runs whenever a new file is added.

---

### 2. Send Email Node - Share File via Email
- **What It Does:** Shares the newly detected file via email with the specified recipient(s).
- **How to Set It Up:**
  - Configure the **recipient's email address**.
  - Include the **file URL** from the Google Drive node in the email body for easy access.
  - Add the **file name** in the email subject or body to inform the recipient about the new file.

---

### 3. Airtable Node - Store File Metadata
- **What It Does:** Logs the file's metadata into an Airtable table for record-keeping and easy tracking.
- **Metadata Includes:**
  - File Name
  - File ID
  - Creation Time
  - Modification Time
  - Recipient Email
- **How to Set It Up:**
  - Connect to your **Airtable base and table**.
  - Map the required fields from the Google Drive and Email nodes to corresponding Airtable columns.

---

## 📊 Outcome
✅ New files are automatically shared with recipients.  
✅ File metadata is securely logged for reference and tracking.  
✅ Manual work is eliminated, improving efficiency and reducing the chance of human error.

---


## 🚀 Benefits
✅ Automated file sharing and logging  
✅ Centralized file metadata management  
✅ Time-saving and error-free process  
✅ Easily track which files were sent and to whom

---

## 📌 Example Use Cases
- Automating document delivery to clients
- Tracking project file submissions
- Logging important business files for auditing
- Sharing reports while maintaining metadata records

---
## 🌐 About WeblineIndia
**WeblineIndia** specializes in delivering **innovative AI and automation solutions** to simplify and streamline business processes.

Need help customizing this workflow or building similar solutions? Feel free to reach out to our team!

---
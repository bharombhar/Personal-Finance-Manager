# Budget Bharat Pro: Personal Finance Manager

[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://www.google.com/script/start/)
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)](https://www.google.com/sheets/about/)
[![Google Forms](https://img.shields.io/badge/Google%20Forms-7B42BC?style=for-the-badge&logo=google-forms&logoColor=white)](https://www.google.com/forms/about/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Budget Bharat Pro** is a comprehensive personal finance management tool built entirely on Google Apps Script, Google Forms, and Google Sheets. Track your daily income, expenses, and manage money lent or loaned to individuals, all from a simple, mobile-friendly Google Form.

This tool is designed for easy setup and personal use—simply make a copy on your own Google Drive to get started!

---

## ✨ Key Features

* **📊 Comprehensive Tracking:** Log daily expenses, income, and manage lent/loan transactions.
* **🧠 Dynamic Forms:** The Google Form fields (like Categories or Person Names) automatically update based on the values you set in the main Google Sheet.
* **🧾 Individual Ledgers:** Automatically creates a separate, neatly formatted sheet for each person you transact with, showing a complete history and remaining balance.
* **🤖 One-Click Automation:**
    * **Generate PDFs:** Create a PDF summary of any individual's transaction history.
    * **Send Emails:** Email transaction summaries directly from the sheet.
    * **WhatsApp Reminders:** Send personalized payment reminders via WhatsApp.
* **📁 Automatic File Organization:** Automatically creates folders in your Google Drive to store transaction attachments.
* **📱 Mobile Friendly:** Add transactions on the go using the Google Form on your phone.
* **🔧 Fully Customizable:** Easily add your own expense/income categories, modify the layout, and adapt the App Script code to your needs.
-- in Progress --
*  **📱 PhonePe transaction Daily data Scrapper:** to tract, extract & get summary of your daily PhonePe spendings right inside this tool 📱.
---

## 🚀 Getting Started

To get your own copy of Budget Bharat Pro up and running, follow these simple steps.

### **Prerequisites**

* A Google Account.

### **Installation**

1.  **Copy the Project Folder**
    * Click this link to access the shared folder: **[https://drive.google.com/drive/folders/1iWz-Xg6tdBG_tyvV6y49EGqE7KEWghFH](https://drive.google.com/drive/folders/1iWz-Xg6tdBG_tyvV6y49EGqE7KEWghFH)**
    * Right-click the main folder and select **"Make a copy"**. This will save the entire folder structure, including all files, to your own Google Drive.

2.  **Initial Configuration (In the Main Sheet)**
    * Open your copied folder and then open the **"S Budget Bharat (Responses)"** Google Sheet.
    * Navigate to the **"Form Edit Code"** tab at the bottom.
    * **Customize Your Form Fields:**
        * Add your personal expense `Category` items in the designated column.
        * Add your `Income Type` options.
        * Add `Person` names for tracking loans.
    * **Add Admin & Contact Details:**
        * Fill in the **Admin Details** table. This will be used for sending customized emails and summaries.
        * To use the WhatsApp feature, fill in the contact details for each person in the provided table.

3.  **Run Macros & Set the Triggers**
    * In the **"S Budget Bharat (Responses)"** on **"Form Code Edit"** sheet Run Appscripts using dropdown if on mobile or buttons if on desktop`**.
    * In the **"S Template_Debtor"** on **"Trans_Record"** sheet Run Appscripts using dropdown if on mobile or buttons if on desktop`**.
    * Run the macro named **`Set Triggers`** , **`Borders`**.
    * Google will ask for authorization. **You must approve these permissions** for the script to function. This one-time setup enables all the automation!
    * once you get authorization you can run any macro from your mobile device as well no need to log in on desktop thats previlage here right? 
You are now ready to go!

---
## 🔗 Direct Links to Core Components

* **[Google Form](https://docs.google.com/forms/d/1ld7rRIF8PudmhTkW_X9d1yqD2mkXMI1CTlv9lasIJyU/preview?edit_requested=true)**: The main form for inputting all your transactions.
* **[Main Response & Edit Sheet](https://docs.google.com/spreadsheets/d/1_kIYgNsfXDjhMODtmZJsg2gHG3YUmJknpnS7b1q4Zs4/edit?gid=868221467#gid=868221467)**: Where all data is stored and where you configure the tool.
* **[Template Sheet](https://docs.google.com/spreadsheets/d/1cKFHVQTDWC-4EtWHQbhofCA9us2IWubShviRkZbmsNc/edit?gid=785942291#gid=785942291)**: The template used to create individual ledgers for each person.

---

## 🛠️ Usage

1.  **Input Transactions:**
    * Open and use the **"Budget Bharat" Google Form** to input your daily spending and income. You can bookmark this form on your mobile device for quick access.
2.  **View Data:**
    * All your form responses will be collected in the **"S Budget Bharat (Responses)"** sheet., extra sheets to ref to **'data'** , **'PER_SUMMARY'** etc.
3.  **Manage Individual Ledgers:**
    * The script will automatically create new sheets named after the individuals you transact with.
    * Open an individual's sheet to see their complete transaction table.
    * Use the buttons (**`SAVE PDF`**, **`SEND MAIL`**, **`Send REMINDER WhatsApp`**) to perform actions for that specific person.

---

## 🙏 Contributing

Contributions are welcome! If you have any suggestions or find any issues, please feel free to submit a pull request or open an issue.

---

## 👤 Author

**Bharat Rasve**

Follow Bharat Rasve for more great projects and content:

* **Twitter:** [https://lnkd.in/dumhzwzK](https://lnkd.in/dumhzwzK)
* **Instagram:** [https://lnkd.in/dmtbG9iu](https://lnkd.in/dmtbG9iu)
* **Quora:** [https://lnkd.in/dsZvEmNh](https://lnkd.in/dsZvEmNh)
* **YouTube:** [https://lnkd.in/dkZTNjsU](https://lnkd.in/dkZTNjsU)

---

## 📜 License

Distributed under the MIT License. See the `LICENSE` file for more information.

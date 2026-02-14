# n8n-lead-automation-academia
Lead automation workflow built with n8n (Google Sheets + Gmail).

# n8n Lead Automation – Academy Example

## 📌 Overview

This project showcases a production-minded lead automation workflow built with **n8n**.

It simulates a real-world scenario where a small academy receives new student inquiries through a form and needs to automate the internal handling process.

The workflow:

- Stores lead data in Google Sheets
- Sends an internal notification email
- Sends a personalized confirmation email to the student
- Validates that the email field is not empty before sending

Although simple, this project focuses on understanding data flow, validation logic, and clean workflow design.

---

## 🛠 Tech Stack

- n8n (Workflow Automation)
- Google Sheets API
- Gmail API

---

## ⚙ Workflow Logic

1. Manual Trigger (simulation of form submission)
2. Data preparation using "Edit Fields"
3. Append row to Google Sheets
4. Conditional validation using IF node
5. Internal email notification
6. Automated personalized response to the lead

---

## 🧠 Key Concepts Practiced

- JSON data flow between nodes
- Difference between `$json` and referencing specific nodes
- Conditional branching with IF nodes
- Dynamic expressions in email templates
- Basic workflow validation
- Clean separation between data source and output logic

---

## 🚀 Possible Improvements

- Replace Manual Trigger with a Webhook trigger
- Add lead tagging/classification logic
- Implement structured error handling
- Integrate with a CRM system
- Add logging and monitoring

---

## 📂 How to Use

1. Import `workflow.public.json` into n8n
2. Connect your own Google Sheets credentials
3. Connect your Gmail credentials
4. Replace the Sheet ID with your own
5. Execute the workflow

## Workflow Screenshot
![Workflow Screenshot](screenshots/workflow.png)


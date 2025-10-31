# Appointment-schedule-Reminder-
Appointment Reminder Automation (No-Code n8n Workflow)
# Appointment Reminder Automation (No-Code n8n Workflow)

This project automates appointment reminder emails for clinics, salons, and consultants — helping reduce missed appointments.  
It is built entirely on **n8n**, without writing a single line of code.

---

##  **Workflow Overview**

**Trigger:**  
Schedule Trigger node runs daily at a fixed time.

**Steps:**
1. **Google Sheets Node** – Fetches patient data (Name, Email, Appointment Date, Reminder Status).  
2. **IF Node** – Checks if appointment is scheduled for the next day.  
3. **Gmail Node** – Sends an automated reminder email.  
4. **Google Sheets Update Node** – Marks the “Reminder Sent” status as “Yes”.

---

##**Value for Clients**
- Saves front-desk staff hours of manual follow-up
- Fully customizable to fit any appointment-based business (clinics, salons, consultants, etc.)

---

##  **Tech Stack**

- **Platform:** n8n (Self-hosted)
- **Data Source:** Google Sheets
- **Email Service:** Gmail
- **Automation Logic:** No-code conditional checks

---

##  **Demo Video**

 [Click here to watch the workflow in action](https://youtu.be/kso_eQA_z0Q)

---

## 📂 **Files Included**

- `appointment-reminder-workflow.json` – Exported n8n workflow file  
- `README.md` – Project documentation  

---

##  **How to Use**

1. Import the workflow JSON into your **n8n** instance.  
2. Connect your Google Sheets and Gmail credentials.  
3. Adjust column names in nodes (if needed).  
4. Schedule the workflow via schedule trigger node to run daily.  
5. Test with a dummy email before real deployment.

---

##  **Author**

**Ayesh Ashraf**  

--- 

# ANIKET-SHEGAMWAR-g2-sap
# 📊 Employee & Student Data Management using ABAP  

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/59/SAP_2011_logo.svg" width="150"/>
</p>  

🚀 This is a **complete ABAP-based project** developed during my internship at **SURE Trust, Puttaparthi (Andhra Pradesh)** under the guidance of **Mr. Santosh Pal (SAP ABAP Consultant)**.  

The project brings together different ABAP components — **Dictionary Objects, Module Pool Programming, Classical Interactive Reports, Excel Integration, and Smart Forms** — to provide a practical solution for **managing employee and student records inside SAP ERP**.  

It simulates a real enterprise scenario where organizations need to **store, update, analyze, and generate professional reports** of employee and student information.  

---

## ✨ Key Features  

- 🗄️ **Custom Database Tables**  
  - Created two custom tables:  
    - `ZEMPLOYEE` → for employee details (ID, Name, Designation, Salary).  
    - `ZSTUDENT` → for student details (ID, Name, Division, Roll Number).  
  - Provides structured and centralized storage of data.  

- 🛠️ **Table Maintenance Generator (TMG)**  
  - Enabled for both tables to allow CRUD operations directly via **SM30**.  
  - Makes it possible for end-users (without coding) to maintain records.  

- 💻 **Module Pool Program**  
  - Interactive screens created with navigation using radio buttons.  
  - Separate screens for **employee data entry/update** and **student data entry/update**.  
  - Real-time update and display of records from SAP GUI.  

- 📑 **Classical Interactive Reporting**  
  - Employee report with **drilldown capability**: clicking on Designation/Division shows all related employees.  
  - Student report displaying structured academic details.  
  - Demonstrates use of **AT LINE-SELECTION** for multi-level reporting.  

- 📥 **Excel Export Utility**  
  - Custom program to export report data into **Excel/XML format** using `GUI_DOWNLOAD`.  
  - User provides file path, making the export flexible and environment-independent.  

- 🖨️ **Smart Forms**  
  - Two Smart Forms designed:  
    - Employee Smart Form  
    - Student Smart Form  
  - Features included: **company logo, address header, page numbers, tabular data layout**.  
  - Outputs professional, printable reports just like real business documents.  

---

## 🛠️ Tools & Technologies  

- **SAP GUI 7.7** – Development environment.  
- **ABAP Dictionary (SE11)** – Custom tables, domains, data elements.  
- **Table Maintenance Generator (SM30)** – Data maintenance.  
- **Module Pool Programming (SE80)** – Custom SAP GUI screens.  
- **Classical Reports** – Interactive employee reports with drilldown.  
- **Smart Forms (SE71)** – Professional printable reports.  
- **GUI_DOWNLOAD** – Excel/XML data export.  

---

## 🎯 Objectives  

✔️ Build a **robust and scalable SAP ABAP application** to manage employee & student data.  
✔️ Provide **easy record maintenance** via TMG and interactive module pool screens.  
✔️ Enable **drilldown-based reporting** for employee insights by Designation/Division.  
✔️ Allow **offline analysis** by exporting data into Excel format.  
✔️ Deliver **professionally branded reports** using Smart Forms with logos, headers, and structured layouts.  
✔️ Gain **end-to-end SAP ABAP development experience** covering Dictionary, Screens, Reports, ALV, and Smart Forms.  

---

## 🌱 Future Scope  

- 🌐 **SAP Fiori/UI5 Frontend**  
  - Replace SAP GUI screens with modern, web-based Fiori apps.  
  - Provide responsive layouts accessible on desktops, tablets, and mobiles.  

- 🔔 **Workflow Integration**  
  - Add approval process for employee/student updates.  
  - Example: changes in salary or division require manager approval before activation.  

- 📄 **Smart Form Enhancements**  
  - Extend forms to support direct **PDF export and email delivery**.  
  - Makes reports usable outside SAP for official communication.  

- ☁️ **Cloud Deployment on SAP BTP**  
  - Move the application to **SAP Business Technology Platform (BTP) – ABAP Environment**.  
  - Enables RAP (RESTful ABAP Programming Model), integration with SAP Analytics Cloud, and scalability for enterprise use.  

---

## 👨‍💻 Author  

**Aniket Shegamwar**  
🎓 B.Tech – Electronics & Communication Engineering  
💼 SAP ABAP Intern at **SURE Trust**  
📍 Nagpur, India  

🔗 [GitHub Profile](https://github.com/sure-trust/ANIKET-SHEGAMWAR-g2-sap)  

---

⭐ If you liked this project, don’t forget to **star the repo** and share feedback! ⭐

# Employee Audit Logging System

## 📌 Project Overview

The Employee Audit Logging System is a frontend-based simulation of database triggers and views using HTML, CSS, and JavaScript.

This project demonstrates how INSERT and UPDATE operations can be automatically logged (Trigger Simulation) and how daily activity reports can be generated dynamically (View Simulation).

It mimics real-time enterprise audit logging systems used in large-scale applications.

---

## 🚀 Features

- Add new employee (INSERT simulation)
- Update existing employee (UPDATE simulation)
- Automatic audit logging
- Daily activity report generation
- Data persistence using LocalStorage
- Clean UI with structured layout

---

## 🏗️ Project Structure

audit-logging-system/
│
├── index.html
├── style.css
├── script.js
└── README.md


---

## 🧠 Concepts Implemented

| Database Concept | Web Implementation |
|------------------|--------------------|
| Trigger          | JavaScript event listener |
| Audit Table      | JavaScript Array + LocalStorage |
| View             | Aggregated Daily Report |
| INSERT/UPDATE    | Conditional logic inside JS |

---

## 💻 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Browser LocalStorage API

---

## 🔧 How to Run the Project

1. Download or clone the project folder.
2. Open `index.html` in any modern browser.
3. Add employee details and click **Save**.
4. Update same Employee ID to simulate UPDATE trigger.
5. View audit log and daily report automatically.

No server or installation required.

---

## 📊 System Workflow

1. User enters employee details.
2. JavaScript checks if employee ID already exists.
3. If not → INSERT operation logged.
4. If exists → UPDATE operation logged.
5. Audit log is stored in LocalStorage.
6. Daily report aggregates logs by date.

---

## 🏢 Real-World Relevance

Audit logging is widely used in enterprise systems for:

- Banking transactions
- Payroll systems
- E-commerce platforms
- Healthcare records
- ERP systems

Major companies like:
- Microsoft
- Amazon
- Oracle

use audit mechanisms to track data changes and ensure compliance.

---

## 🎯 Learning Outcomes

- Event-driven programming
- DOM manipulation
- Data persistence
- Aggregation logic
- Simulation of database triggers
- Structured frontend project organization

---

## 📌 Future Enhancements

- Add DELETE logging
- Add user authentication
- Add export to CSV functionality
- Convert to Node.js + MySQL backend
- Deploy on cloud platform

---

## 👨‍💻 Author

Kapil Charan  
B.Tech Computer Science Engineering 
Expected Graduation: 2027

---

## 📜 License

This project is for educational and academic purposes.

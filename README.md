# 📊 Amazon Payments Reconciliation & Monitoring Portal (Frontend)

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)
![SAP Business One](https://img.shields.io/badge/SAP_Business_One-0FAAFF?style=flat&logo=sap&logoColor=white)

## 📌 Project Overview
This platform provides an automated full-stack solution for reconciling invoices, settlements, fees, and payments between **Amazon** and **SAP Business One**, significantly improving financial accuracy and operational efficiency over manual spreadsheet processes.

Hosted on **IDA Cloud**, this **React** web portal enables finance and operations teams to perform real-time settlement monitoring, discrepancy management, Pareto exception analysis, and automated reporting connected to a **Node.js + SAP HANA** backend.

🔗 **Companion Backend Repository:** [Backend-Amazon-Payments-reconciliation (Node.js & SAP HANA API)](https://github.com/Anguibell/Backend-Amazon-Payments-reconciliation)

---

## ✨ Key Capabilities
- **Executive KPI & Pareto Dashboards:** Interactive data visualization powered by **Chart.js** (`react-chartjs-2`) to track settlement statuses, fee discrepancies, and global exception trends.
- **End-to-End Financial Traceability:** Dedicated views for Orders, Sales, Incoming Payments, Fees, Settlement Details, and General Ledger (GL) summaries.
- **Automated Audit & Reporting Exports:** Built-in generation of downloadable reconciliation reports in **PDF** (`jspdf`, `jspdf-autotable`) and **CSV** (`react-csv`) formats for accounting audits.
- **Dynamic API Integration:** Communicates asynchronously with the Node.js / SAP HANA backend dispatcher to filter large transaction volumes by date range, execution status, and processing engine.

---

## 🛠️ Tech Stack & Libraries
- **Core Frontend:** React, JavaScript (ES6+), HTML5, CSS3
- **Data Visualization:** `chart.js`, `react-chartjs-2`
- **Report Generation (PDF & CSV):** `jspdf`, `jspdf-autotable`, `react-csv`
- **Cloud & Backend Integration:** Hosted on IDA Cloud, consuming REST APIs backed by Node.js, Express, and SAP HANA Stored Procedures.

---

## 📦 Installation & Local Development

1. **Install core dependencies:**
   ```bash
   npm install
   ```

2. **Install charting and reporting libraries (if setting up from scratch):**
   ```bash
   npm install react-chartjs-2 chart.js react-csv
   npm install jspdf jspdf-autotable
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Inspect project structure (optional):**
   ```bash
   tree -I node_modules
   ```

---

## 👩‍💻 Developer
- **Author:** [Anguibell Romero](https://www.linkedin.com/in/anguibell-romero) – Systems Engineer
- **Frontend Repository:** [https://github.com/Anguibell/Amazon-Payments-reconciliation](https://github.com/Anguibell/Amazon-Payments-reconciliation)
- **Backend Repository:** [https://github.com/Anguibell/Backend-Amazon-Payments-reconciliation](https://github.com/Anguibell/Backend-Amazon-Payments-reconciliation)

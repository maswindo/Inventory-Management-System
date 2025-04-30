# Inventory Management System

A fully automated inventory tracking and forecasting solution built in Google Sheets and Apps Script, developed to manage materials across 4 warehouses and over 30 service trucks. This system powers real-time material visibility, predictive restocking, and usage-based demand planning for a fast-growing pest control company.

---

## 📦 What This System Does

- **Tracks inventory levels** by warehouse and technician truck
- **Logs all transfers** of material between warehouses and field staff
- **Calculates reorder needs** based on minimum thresholds
- **Forecasts demand** based on historical usage and seasonality
- **Automates invoice updates** to adjust stock levels on arrival
- **Standardizes materials and units** across various vendor formats

---

## 🧰 Tech Stack

| Tool / Language       | Purpose                                           |
|-----------------------|---------------------------------------------------|
| **Google Sheets**     | Main inventory platform and data interface        |
| **Google Apps Script**| Backend automation, logic, and syncing processes |
| **Excel**             | Legacy modeling and forecasting templates         |
| **Tableau**           | Visualization and trend dashboards (in progress) |

---

## 📁 Key Modules

| Module              | Description                                                             |
|---------------------|-------------------------------------------------------------------------|
| `Database Sheet`    | Live record of all materials and their quantities per location          |
| `Transfer Log`      | Logs all warehouse ⇄ truck movements and updates inventory accordingly  |
| `Reorder Levels`    | Minimum thresholds per item and location                                |
| `Clean On-Hand`     | Processes PestPac exports into standardized data                        |
| `Invoice Input`     | Automatically updates stock levels from new shipment invoices           |

---

## 🔄 Automation Highlights

- ⚙️ **Apps Script Functions** to:
  - Auto-update stock from invoice sheets
  - Match item names across systems
  - Trigger reorder alerts via conditional formatting
- 📈 **Forecasting Logic** to:
  - Use past months' transfer and usage data
  - Flag spikes in product usage
- 🔍 **Usage Tracker** that compares warehouse vs. truck movements to identify inconsistencies

---

## 🧠 Why I Built This

When I joined my company, inventory tracking was completely manual and error-prone. There was no reliable way to know how much stock we had, what materials were moving, or when to reorder. I designed this system from the ground up to solve those problems — and it now supports real-time inventory control for a company generating $17M+ annually.

---

## 🚧 In Progress

- Adding barcode-ready version for scanner compatibility
- Migrating forecasting engine from Excel to DuckDB
- Embedding Tableau dashboards for executive insights

---

📫 Contact me: [masonhotalingcs@gmail.com](mailto:masonhotalingcs@gmail.com)  
🌐 Portfolio: [maswindo.github.io](https://maswindo.github.io)  

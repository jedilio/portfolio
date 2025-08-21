# Retail Markdowns Project

## 📌 Overview
This project automates markdown list creation for retail stores.  
Managers previously had to manually cross-check price changes in MIM; I built a Python solution that:
- Matches store inventory with corporate markdown lists
- Produces store-specific markdown files
- Saves hours of manual effort across the fleet

---

## ⚙️ Tech Stack
- **Python (pandas, openpyxl, matplotlib)**
- **Excel automation**
- **PDF generation (matplotlib + reportlab)**

---

## 🔑 Key Features
- Automatically matches markdowns against live store inventory
- Generates Excel and PDF reports per store
- Groups by **site**, **style**, **width**, and **price**
- Adds **summary sheet** with per-site markdown % and averages

---

## 📊 Example Output
*(You can embed images of the Excel/PDF output if you upload them to `assets/`)*

![Markdown Example](../assets/retail-markdowns-sample.png)

---

## 📂 Files
- [`retail_markdowns.py`](../assets/retail_markdowns.py) → Main Python script
- Example markdown reports in `/assets`

---

## 🔗 Back to Portfolio
[← Return to main portfolio](../README.md)

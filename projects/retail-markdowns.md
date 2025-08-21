# Store Specific Markdowns Project

## 📌 Overview
This project automates Store Specific price change list creation for retail stores.  
Managers previously had to manually cross-check price changes in MIM (Merchandise Inventory Management); I built a Python solution that:
- Matches store inventory with corporate markdown lists
- Produces store-specific markdown files
- Saves hours of manual effort across the fleet

This presentation was created to pitch the project to the Allocation Department and gain approval.
[📑 View the Presentation to the Allocation Department (PDF)](../assets/Inventory%20Markdown%20Merge%20Project.pdf)

---

## ⚙️ Tech Stack
- **Python (pandas, openpyxl, matplotlib)**
- **Excel automation**
- **PDF generation (matplotlib + reportlab)**
- **Microsoft Powerpoint**

---

## 🔑 Key Features
- Automatically matches markdowns against current store inventory
- Generates Excel and PDF reports per store
- Groups by **site**, **style**, **width**, and **price**
- Adds **summary sheet** with per-site markdown % and averages to show impact.

---

## 📊 What This Project Does (No Data Shared)

```mermaid
flowchart LR
  A[Markdown List.xlsx] & B[Inventory.xlsx] --> C["Clean & Normalize\n(trim to 8-digit GENERIC ID, parse for widths)"]
  C --> D["Key-Based Merge (GENERIC ID)"]
  D --> E["Filter to Site + Relevant Styles"]
  E --> F["Sort and Format (store-friendly sequence for associates)"]
  F --> G[["Per-Site Outputs (PDF) and Summary Sheet for Allocation Department"]]
```

![Markdown Example](../assets/retail-markdowns-sample.png)

---

## 📂 Files
- [`retail_markdowns.py`](../assets/retail_markdowns.py) → Main Python script
- Example markdown reports in `/assets`

---

## 🔗 Back to Portfolio
[← Return to main portfolio](../README.md)

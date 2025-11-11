# 📊 EAS Supplier Compliance Analysis

This repository contains a Jupyter Notebook designed to track supplier compliance with the **EDI 846, 852, 856 (Inventory Advice, Production Data, Shipments)** data transmission standards. The analysis is organized into two main components:

---

## 1. Year-over-Year Compliance Status

- Performs a detailed, per-record analysis of all suppliers.  
- Determines the current compliance status based on receipt of the latest **846 Inventory Data**.  
- Provides overall compliance rates and highlights suppliers who have **stopped sending data**.  
- Steps covered: **1–6** in the notebook, including data loading, parsing, classification, and visualization.  

---

## 2. Location-Level Risk Scoring (846, 856, 852)

- Calculates compliance scores for multiple EDI types:  
  - **846:** Inventory Data  
  - **856:** Ship Data  
  - **852:** Production Plan & Actual Data  
- Categorizes **risk levels** by location and item category.  
- Identifies recurring problem areas for **non-compliant suppliers** and supports **risk-based monitoring**.  

---

# Supply Chain Correlation Matrix Analysis

This repository contains a **correlation matrix visualization** of key supply chain metrics for a major automotive manufacturer. The analysis provides insights into relationships between supplier performance variables to support **data-driven decisions** in procurement, inventory management, and cost optimization.

---

## 📊 Business Context

OptimalFlow Logistics was engaged to analyze **73 procurement transactions** over the past quarter. The goal is to understand how different supply chain metrics interact to identify:

- Bottlenecks in the supplier network  
- Opportunities to optimize inventory levels  
- Cost reduction strategies through better supplier selection  

Key metrics analyzed include:

| Metric                 | Description                                |
|------------------------|--------------------------------------------|
| Supplier_Lead_Time      | Days from order placement to delivery      |
| Inventory_Levels        | Current stock quantities (units)           |
| Order_Frequency         | Number of orders placed per month          |
| Delivery_Performance    | On-time delivery rate (%)                  |
| Cost_Per_Unit           | Unit cost in dollars ($)                   |

---


---

## 📈 Visualization Details

- **Tool Used:** Microsoft Excel  
- **Analysis:** Correlation matrix using Data Analysis ToolPak  
- **Heatmap:** Conditional formatting with **Red (low) – White – Green (high)** color palette  
- **Purpose:** Identify relationships between supply chain variables for executive decision-making  

### Excel Steps

1. Enable **Data Analysis ToolPak**: File → Options → Add-ins → Analysis ToolPak  
2. Navigate to **Data → Data Analysis → Correlation**  
3. Select the 5 metrics columns, check **Labels in first row**, output to new worksheet  
4. Apply **Conditional Formatting → Color Scales** to correlation values  
5. Export correlation matrix as **correlation.csv**  
6. Take a screenshot of the heatmap as **heatmap.png** (400x400 to 512x512 pixels)  

---

## 📧 Verification

This submission was prepared by **23f2001691@ds.study.iitm.ac.in**. The email is included for verification purposes.

---

## 📥 How to Use

1. Open `correlation.csv` in Excel or any spreadsheet software to review the numeric correlation values.  
2. View `heatmap.png` for a visual interpretation of relationships between metrics.  
3. Use insights for **supplier optimization, inventory planning, and cost reduction strategies**.

---

The heatmap provides a clear, executive-friendly visual summary of correlations among key supply chain metrics.

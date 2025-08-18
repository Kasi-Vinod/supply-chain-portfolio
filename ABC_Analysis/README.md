# ABC Analysis & Multi-Criteria ABC Analysis

## 📌 Project Overview
This project demonstrates **ABC Analysis** and **Multi-Criteria ABC Analysis** techniques for inventory classification.  
The goal is to prioritize items based on consumption value and other business criteria, helping organizations focus on the most impactful SKUs.

---

### Files Included
- [ABC & Multi criteria ABC analysis.xlsx](ABC%20&%20Multi%20criteria%20ABC%20analysis.xlsx) → Excel file containing raw data and analysis.
- `visuals/` → Folder containing charts and output images

<p align="center">
  <img src="visuals/Chart_1.png" alt="Chart_1" width="45%"/>
  <img src="visuals/Chart_2.png" alt="Chart_2" width="45%"/>
</p>

---

🔑 Methodology
1. Segmentation in Inventory Management

Segmentation helps organizations classify inventory items based on impact, instead of treating all items equally. This ensures better control and optimized resource allocation.

2. ABC Analysis (Single-Criterion)

Basis: Annual consumption value (Sales × Unit Price).

Approach:

Rank items in descending order of revenue contribution.

Classify into:

A: Top ~70–80% contribution (high-value items).

B: Next ~15–20%.

C: Remaining low-value items.

Use Case: Prioritize monitoring, tighter control, and frequent review of "A" items.

3. Multi-Criteria ABC Analysis

Basis: Multiple factors, not just sales. Example criteria:

Revenue contribution.

Lead time.

Demand variability.

Criticality (business impact if stockout occurs).

Approach:

Assign weights to each criterion.

Compute a composite score.

Re-rank and classify SKUs into A, B, C segments.

Use Case: More holistic prioritization where low-revenue but critical or high-risk items also get visibility.

---
## 🔑 Key Steps
1. **Data Preparation** – Extract sales/inventory data from the system.  
2. **ABC Analysis** – Rank SKUs based on cumulative consumption value.  
3. **Multi-Criteria ABC** – Include additional factors such as lead time, criticality, or stock-out risk.  
4. **Visualization** – Show class distribution and cumulative contribution via Pareto charts.

---

## 📊 Business Impact
- Improved focus on high-value and critical items.  
- Optimized inventory holding cost.  
- Better supplier management and procurement planning.  

---

## 🚀 How to Use
1. Open the Excel file to explore the calculations.  
2. Refer to the charts in the  file for graphical interpretation.  
3. Apply the framework to your own inventory dataset.  

# Inventory Optimization & Workforce Planning Analytics

## BDM Capstone Project

A descriptive business analytics study focused on inventory
optimization, procurement planning, workforce availability,
and service-operation performance at Ashmiti Enterprise.

---

## Project Overview

This project applies descriptive business analytics to operational
records covering inventory, procurement, workforce attendance,
service visits, and credit transactions.

The objective was to identify operational patterns and translate
them into actionable recommendations for inventory control,
procurement planning, workforce contingency planning, and
service-quality improvement.

### Key Business Questions

1. How concentrated is the organisation's inventory value?
2. How variable is monthly procurement expenditure?
3. Which inventory categories require greater managerial attention?
4. Is workforce availability associated with service-level performance?
5. What is the overall quality of service operations?
6. How does credit transaction activity relate to procurement expenditure?

---

## Data

The analysis used business and operational records covering:

- Purchase Register — January to June 2026
- Credit Transaction Register — January to June 2026
- Godown / Inventory Summary — 193 inventory records
- Workforce Attendance — 936 employee-day records
- Service Operations — 360 service visits
- Workforce data covered 12 employees during April–June 2026

---

## Analytical Methods

### Inventory & Procurement

- Descriptive statistics
- Procurement trend analysis
- Coefficient of variation
- Inventory value concentration
- ABC inventory classification

### Workforce & Service Operations

- Attendance analysis
- SLA compliance analysis
- Service quality analysis
- First-Time Fix Rate
- Repeat Visit Rate
- Complaint Rate
- Descriptive comparison of attendance status and SLA performance

### Financial Context

- Credit transaction trend analysis
- Pearson correlation
- Coefficient of determination (R²)

---

## Key Findings

### Inventory

8 A-class inventory categories accounted for:

**69.55% of classified inventory value**

The five highest-value categories accounted for:

**57.28% of classified inventory value**

This indicates that inventory-management effort should be
prioritised toward high-value categories.

### Procurement

Monthly procurement expenditure had a:

**32.73% coefficient of variation**

indicating substantial month-to-month variation.

### Workforce & SLA

SLA compliance was:

| Attendance Status | SLA Compliance |
|---|---:|
| Present | 93.59% |
| Late | 67.65% |
| Half-day | 100.00% |
| Absent – Unplanned | 45.83% |
| Absent – Approved | 62.50% |

The analysis indicates an observed association between workforce
attendance status and SLA performance. It does not establish
causality.

### Service Quality

- First-Time Fix Rate: **89.17%**
- Repeat Visit Rate: **10.83%**
- Complaint-Free Rate: **91.94%**
- Complaint Rate: **8.06%**
- Average Customer Rating: **4.42 / 5**

### Procurement vs Credit Transactions

Pearson correlation:

**r = 0.07**

Coefficient of determination:

**R² = 0.49%**

The result indicates a very weak linear association. Due to the
small number of monthly observations, this should be interpreted
as preliminary descriptive evidence.

---

## Business Recommendations

### Inventory & Procurement

- Prioritise A-class inventory for frequent review
- Conduct regular monthly procurement reviews
- Incorporate inventory requirements and ABC classification into
  procurement decisions
- Add consumption and stock-velocity measures to future ABC analysis
- Introduce reorder points and safety-stock analysis when demand
  and lead-time data become available

### Workforce & Service

- Maintain backup personnel for critical service requirements
- Prioritise critical service visits during workforce shortages
- Record reasons for repeat visits
- Improve pre-visit diagnosis and spare-parts preparation
- Categorise customer complaints by service type and machine model
- Align technician skills with service requirements and geographic
  routes

---

## Tools

- Google Sheets
- Tally ERP business records
- Descriptive statistics
- ABC analysis
- Correlation analysis
- Data visualisation

---

## Limitations

- Business transaction analysis covered only six months
- Workforce and service analysis covered three months
- Procurement-credit correlation was based on only six observations
- Analysis was restricted to the records made available for the project
- Findings are descriptive and should not be interpreted as causal
  evidence or definitive forecasts

---

## Project Deliverables

- [Final Report](report/BDM_End_Term_Report.pdf)
- [Viva Presentation](presentation/BDM_Viva_Presentation.pdf)

---

## Author

**Arpit Kumar Mishra**

IIT Madras — BS Degree Program

BDM Capstone Project | May Term 2026

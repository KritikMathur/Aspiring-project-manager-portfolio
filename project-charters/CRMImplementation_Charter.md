# Project Charter: Salesforce CRM Insights Dashboard

**Project Title:**  
Salesforce CRM Insights Dashboard

**Project Sponsor:**  
Anita Rao, Head of Sales

**Project Manager:**  
Kritik Mathur, Associate Project Manager (APM Candidate)

**Date of Authorization:**  
June 20, 2025

---

## 1. Project Purpose & Background  
Our Sales organization currently relies on manual exports and spreadsheets to track pipeline health, rep performance, and win/loss rates. To accelerate decision‐making and improve visibility, this project will deliver a self-service Power BI dashboard connected directly to Salesforce CRM, automating weekly reporting and enabling deeper analytics.

---

## 2. Objectives & Success Criteria  

| Objective                                                              | Success Criteria (KPI)                                           |
|------------------------------------------------------------------------|------------------------------------------------------------------|
| 1. Deliver a prototype dashboard by June 28, 2025                      | • Prototype complete and signed off by stakeholders              |
| 2. Automate weekly PDF report distribution to Sales leadership         | • Reports emailed every Monday by 8 AM without manual effort     |
| 3. Enable real-time visibility into pipeline conversion and aging      | • < 5 % discrepancies vs. live Salesforce data                    |
| 4. Improve data-driven decision-making in sales reviews                | • 80 % of sales managers reference dashboard in weekly reviews   |

---

## 3. Scope  

### In Scope  
- **Data Connection:** Power BI → Salesforce CRM API  
- **Visuals:**  
  - Lead conversion funnel  
  - Opportunity aging heatmap  
  - Regional revenue & win/loss trends  
  - Top-performing reps dashboard  
- **Automation:**  
  - Scheduled weekly PDF export & email delivery via Power Automate  
- **User Acceptance Testing:**  
  - UAT with Sales leadership group  

### Out of Scope  
- Manual data cleanup in Salesforce  
- Integration of non-Salesforce data sources (ERP, marketing)  
- Mobile-optimized or embedded web client (Phase II)

---

## 4. Key Stakeholders & Roles  

| Role               | Name / Team            | Responsibilities                                 |
|--------------------|------------------------|--------------------------------------------------|
| **Project Sponsor**| Anita Rao (Head Sales) | Funding approval, strategic direction            |
| **Project Manager**| Kritik Mathur          | Planning, tracking, stakeholder communication    |
| **BI Lead**        | Karan Mehta            | Data modeling, report development

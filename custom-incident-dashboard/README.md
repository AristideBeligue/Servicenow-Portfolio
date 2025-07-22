# Custom Incident Management Dashboard

## 🔍 Overview
A customized dashboard for IT Managers to monitor incidents in real time using ServiceNow's Incident module, Reports, and Performance Analytics.

## 💡 Use Case
Managers need a single view to monitor team workload, urgent issues, and SLA performance.

## 🧰 Features
- Filter by priority, assignment group, or status
- Key metrics: open incidents, response times
- Reports: Pie chart by priority, bar chart by group
- Auto-assignment business rule by category

## ⚙️ Tools & Modules Used
- Incident Management
- Reports & Dashboards
- Performance Analytics (optional)
- Script: Business Rule for auto-assignment

## 🧪 Demo Steps
1. Navigate to Incident > Reports
2. Create a report with filters: `Active = true AND Priority = 1`
3. Build a dashboard and add 2–3 visualizations
4. Create a Business Rule:
   - Trigger: `Before Insert`
   - Condition: `category == 'network'`
   - Action: `assign to Network Team`
5. Screenshot each step

## 📸 Screenshots
_(Add screenshots of your reports, dashboard, and scripts here)_

## 🧠 What I Learned
- How to use reports and dashboards in ServiceNow
- Writing simple business rules for automation

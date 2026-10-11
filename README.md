# 💰 Project Budget Tracker | Excel Dashboard

**Tools:** MS Excel | Formulas: SUM, SUMIF, IF, Nested IF | Conditional Formatting | Charts

### 📌 Project Overview
Created a dynamic budget tracker to track 10 project tasks across 6 categories. The tracker compares planned budget vs actual cost and gives instant insights on where money was saved or overspent.

### 🔑 Key Features
- **Variance Calculation:** `=C2-D2` and `% Variance = E2/C2`
- **Status Automation:** `=IF(E2>0,"SAVED",IF(E2<0,"OVERSPENT","ON BUDGET"))`
- **Budget Health:** Nested IF for Over Budget / Under Budget / On Budget / Not Started
- **Category Summary:** Used `SUMIF` to aggregate spend by Design, Development, QA, Marketing, Operations, Management
- **Conditional Formatting:** Green for SAVED, Red for OVERSPENT, Yellow for ON BUDGET
- **Dashboard:** Total Planned: ₹4,90,000 | Total Actual: ₹4,78,000 | Saved: ₹12,000 (2%)

### 📊 Visualizations
1. **Bar Chart - Planned vs Actual Cost by Task** - Compare each task's budget performance
2. **Pie Chart - Actual Spend by Category** - Shows 46% spend went to Development, 26% to Marketing etc.

### 🎯 Outcome
Helped identify 4 overspent tasks and 5 saved tasks, resulting in net 2% cost saving. This is how real companies track project budgets.

### 📸 Screenshot

<img width="1920" height="1080" alt="Screenshot (161)" src="https://github.com/user-attachments/assets/be732410-06ac-472c-bbff-dcc488c49f70" />

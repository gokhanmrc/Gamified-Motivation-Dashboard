# 🚀 Personal Reward System: Gamified Performance Dashboard

A behavioral performance framework built with Excel/Google Sheets that turns daily productivity into a virtual economy. This project uses gamification principles, dynamic KPI tracking, and financial discipline to optimize personal motivation and habit consistency.

## 📈 Core Methodology
Unlike traditional budget trackers, this system treats rewards as "fuel" for future performance. It creates a sustainable loop between completing high-value tasks (SQL, Python, Data Projects) and earning "discretionary funds" for personal rewards.

## 🛠 Key Features & KPIs
- **Dynamic KPI Dashboard:** Real-time tracking of Net Motivation Balance, Discretionary Cap, and Performance Slippages.
- **Streak Multiplier:** A mathematical growth factor that rewards consecutive successful days to prevent habit churn.
- **Discipline Debit:** An automated penalty mechanism for missed routines, ensuring accountability.
- **Resource Allocation:** Strategically balancing "Virtual Earnings" from professional tasks with personal reward expenses.

## 🖥 Technical Implementation
- **Tools:** Microsoft Excel / Google Sheets
- **Techniques:** Complex logical formulas (`IF`, `AND`, `TODAY`), Conditional Formatting, Data Validation, and Dynamic Dashboard Design.
- **Structure:** Scalable data tables designed for monthly performance cycles.

## 🚀 How to Use
1. **Direct Access:** [Click here to create your own copy on Google Sheets](https://docs.google.com/spreadsheets/d/1QG8IWCfw90LY3LtkSMxR0SbeUPjp-aDVBCLFrWn_xhU/copy)
2. **Excel Template:** Download the `.xlsx` file from the `/Template` folder in this repository.
3. **Setup:** Define your own tasks, point values, and "Discretionary Cap" value in the Dashboard settings.
---

### 🛠 Data Entry Rules

To ensure the dashboard and bonus mechanisms function correctly, please follow these data entry guidelines:

#### Daily Tracking
- Navigate to the specific date column (e.g., **12 January**).
- Enter the value **`1`** for each completed task.

#### Reward Calculation
- Entering **`1`** triggers the multiplier for that specific task.
- The calculated reward is automatically reflected in **Virtual Earnings** on the Dashboard.

#### Activating Bonuses
- Combo and Recurring Bonuses are based on **consistency**.
- Missing entries will break the bonus chain.

#### Consecutive Entry (Streak Logic)
- For a task completed **3 times consecutively**, enter: 1 | 1 | 1
- The system recognizes this as a **streak** and applies bonus calculations accordingly.

#### Automated Penalties
- The **Discipline Debit** system is fully automated.
- If a date has passed with **no entry**, a penalty is applied automatically.

---

### 💸 Tracking Rewards & Expenses

The system supports direct expense tracking alongside task completion.

#### Direct Expense Entry
- Navigate to the relevant date column.
- Enter the **actual amount spent** next to the related **Target Reward**  
(e.g., `3500` for a game purchase).

#### Automatic Deduction
- Expenses are immediately deducted from **Gross Revenue**.
- **Net Motivation Balance** updates in real time.

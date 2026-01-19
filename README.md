# 🚀 Personal Reward System: Gamified Performance Dashboard
<img width="1851" height="484" alt="gamified" src="https://github.com/user-attachments/assets/7fd0fad8-ccad-4d24-9cf2-212524135da7" />

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
- Navigate to the specific date column (e.g., "12 January") and enter the value "1" for each completed task.

#### Reward Calculation
- Entering "1" triggers the multiplier for that specific task, which then automatically reflects your "Virtual Earnings" on the Dashboard.

#### Activating Bonuses
- To trigger Combo and Recurring Bonuses, you must maintain consistency.

#### Consecutive Entry (Streak Logic)
- For a task performed 3 times, enter "1" in three consecutive cells (e.g., 1 | 1 | 1). This allows the system to recognize the "streak" and calculate bonuses accurately.

#### Automated Penalties
- Remember that the Discipline Debit system is dynamic; if a date has passed and no data is entered, the system will automatically apply a penalty to ensure accountability.

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

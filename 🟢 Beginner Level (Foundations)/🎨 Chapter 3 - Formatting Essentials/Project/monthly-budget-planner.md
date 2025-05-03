# 📚 Chapter 3 Project: Monthly Budget Planner with Conditional Formatting

## ❓ Project Question

> **Task:**  
> Create a Monthly Budget Planner in Excel that includes:
> - Income and expense categories
> - Budget vs. actual spending comparison
> - Conditional formatting to highlight variances
> - Proper cell formatting for currency values
> - Visual indicators of budget status

---

## 🛠️ How to Do It (Answer)

### 1️⃣ Set Up the Basic Structure
- Create these column headers in row 1:
  | Category | Budgeted | Actual | Difference | Status |
  |----------|----------|--------|------------|--------|

- Add income and expense categories in column A:
  - **Income**: Salary, Freelance, Other
  - **Expenses**: Rent, Utilities, Groceries, Transportation, Entertainment, etc.

---

### 2️⃣ Format the Currency Cells
- Select columns B, C, and D
- Apply currency formatting:
  - Home tab → Number group → ₹  symbol
  - Or right-click → Format Cells → Currency

---

### 3️⃣ Add Formulas
- In column D, calculate the difference:
  - For income: `=C2-B2` (Actual minus Budgeted)
  - For expenses: `=B2-C2` (Budgeted minus Actual)
- Create totals row at the bottom using `SUM` function

---

### 4️⃣ Apply Conditional Formatting

#### For the Difference Column:
- Select the Difference column
- Home tab → Conditional Formatting → Color Scales
- Choose a three-color scale:
  - Red for negative values
  - Yellow for near zero
  - Green for positive values

#### For the Status Column:
- Use icon sets to show status:
  - Select Status column
  - Home tab → Conditional Formatting → Icon Sets → 3 Traffic Lights
  - Set rules:
    - Red: < 0 (over budget)
    - Yellow: = 0 (at budget)
    - Green: > 0 (under budget)

---

### 5️⃣ Enhance with Borders and Formatting
- Add borders around the table
- Make headers bold and center-aligned
- Add background color to header row
- Group expense categories (optional)

---

### 6️⃣ Add Summary Section
- Create a summary section showing:
  - Total Income
  - Total Expenses
  - Net Savings/Deficit
- Apply conditional formatting to Net value

---

## 📥 Download Example File

👉 [Download the sample Monthly Budget Planner Excel file](Monthly_Budget_Planner.xlsx)

---

## 💡 Tips for Success

- Use cell comments to add notes about unusual expenses
- Create separate worksheets for different months
- Consider using Freeze Panes to keep headers visible
- Add charts to visualize budget distribution
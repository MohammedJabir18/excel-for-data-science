# Data Validation in Excel

Data Validation in Excel is a powerful feature that allows users to control the type of data or the values that users enter into a cell. It improves data consistency and prevents errors.

---

## 🎯 Purpose of Data Validation

- Ensure data entry accuracy
- Prevent invalid or out-of-range values
- Provide dropdowns for easier input
- Display custom input and error messages

---

## ✅ How to Apply Data Validation

1. Select the cell or range of cells.
2. Go to the **Data** tab on the Ribbon.
3. Click **Data Validation** in the **Data Tools** group.
4. In the dialog box, configure the desired rules under the **Settings** tab.

---

## 📋 Dropdown List (List Validation)

Create a dropdown list from which users can choose a value.

### Steps:

1. Select the target cells.
2. Open **Data Validation**.
3. In the **Allow** field, select **List**.
4. In the **Source** field, type:
   ```
   Apple, Banana, Mango
   ```
   or refer to a range like:
   ```
   =Sheet2!A1:A3
   ```
5. Click **OK**.

---

## 🔢 Other Data Validation Types

| Type       | Description |
|------------|-------------|
| **Whole number** | Only allow integers within a specified range |
| **Decimal** | Allows decimal numbers (e.g., 0.5 to 99.9) |
| **Date** | Restricts to a date or date range |
| **Time** | Restricts to a time or time range |
| **Text Length** | Controls number of characters allowed |
| **Custom** | Use a custom formula to define validation logic |

---

## 🧠 Example: Allow Numbers Between 1 and 100

1. Allow: **Whole number**
2. Data: **between**
3. Minimum: `1`
4. Maximum: `100`

---

## 💬 Input Message (Optional)

- Provides guidance to the user when they select a cell.
- Set under the **Input Message** tab in the dialog.

---

## 🚫 Error Alert (Optional)

- Displays an error if data violates the validation rule.
- You can choose:
  - **Stop** (prevents entry)
  - **Warning** (warns but allows)
  - **Information** (informs only)

---

## 💡 Tips

- Use named ranges for dynamic dropdowns.
- Use formulas like `=ISNUMBER(A1)` for custom validations.
- Combine with conditional formatting for better UX.

---

## 📌 Shortcuts

- Open Data Validation dialog: `Alt + D + L`

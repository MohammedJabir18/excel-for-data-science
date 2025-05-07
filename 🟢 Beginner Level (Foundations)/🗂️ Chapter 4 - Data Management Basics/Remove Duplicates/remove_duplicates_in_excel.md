# Remove Duplicates in Excel

Removing duplicates in Excel is a common task to clean up data, eliminate redundancy, and ensure data accuracy.

---

## 🗑️ Why Remove Duplicates?

- To avoid data redundancy
- To ensure accurate analysis and reporting
- To reduce file size and improve performance

---

## ✅ How to Remove Duplicates

### Steps

1. Select the range of cells or entire table.
2. Go to **Data** ➔ **Remove Duplicates**.
3. In the **Remove Duplicates** dialog, check the columns you want to include in the duplicate check.
4. Click **OK**.
5. Excel will display the number of duplicates removed and the unique values left.

### Example

Consider this dataset:

| Name  | Email              | City      |
|-------|--------------------|-----------|
| Alice | alice@email.com    | New York  |
| Bob   | bob@email.com      | London    |
| Alice | alice@email.com    | New York  |
| Carol | carol@email.com    | Sydney    |
| Bob   | bob@email.com      | London    |

After removing duplicates based on **Name** and **Email**, only unique rows will remain.

---

## 📊 Removing Duplicates Across Multiple Columns

- You can choose multiple columns for duplicate checks.
- For example, removing duplicates based on both **Name** and **Email** ensures only entirely identical rows are removed.

---

## 🔄 Advanced Methods

### Using Power Query

1. Select your data range.
2. Click **Data** ➔ **From Table/Range**.
3. In Power Query Editor, right-click the column and select **Remove Duplicates**.
4. Click **Close & Load** to load the clean data back to Excel.

### Using Formulas

Use Excel functions like **UNIQUE** (Excel 365/2019+) or **Remove Duplicates** in **Power Query** for more control.

```excel
=UNIQUE(A2:B10)
```

---

## 💡 Tips

- Always **backup your data** before removing duplicates.
- Use **Conditional Formatting** to highlight duplicates before removing them.
- Consider using the **COUNTIF** function to identify duplicates before removal.

---

## 📌 Shortcuts

- **Alt + A + M** - Open Remove Duplicates dialog  
- **Ctrl + Z** - Undo a duplicate removal if you make a mistake  

---

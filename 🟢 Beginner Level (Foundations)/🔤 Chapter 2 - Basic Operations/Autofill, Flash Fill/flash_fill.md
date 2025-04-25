
# 📘 Flash Fill in Excel - Quick Guide

Flash Fill is an Excel feature that automatically fills in values when it senses a pattern. It’s useful for:
- Extracting data from cells
- Combining data from multiple cells
- Changing text case
- Formatting numbers or dates
- Reformatting strings like names or IDs

---

## 🔧 How to Use Flash Fill

1. Start typing the desired result in a new column.
2. Press `Enter`.
3. Use the shortcut:  
   **Ctrl + E** (Windows)  
   or  
   Go to **Data** > **Flash Fill**

---

## ✂️ Extracting Data

| Full Name       | First Name |
|------------------|-------------|
| John Doe         | John        |
| Sarah Connor     | Sarah       |
| Michael Jordan   | Michael     |

**Steps**:
- Type "John" next to "John Doe"
- Press `Ctrl + E`  
Excel will fill down the rest.

---

## ➕ Combining Data

| First Name | Last Name | Full Name       |
|------------|------------|------------------|
| John       | Doe        | John Doe         |
| Sarah      | Connor     | Sarah Connor     |
| Michael    | Jordan     | Michael Jordan   |

**Steps**:
- Type "John Doe" in the first row
- Press `Ctrl + E` to combine the rest

---

## 🔠 Changing Text Case

| Name            | Uppercase     |
|-----------------|----------------|
| john doe        | JOHN DOE       |
| sarah connor    | SARAH CONNOR   |
| michael jordan  | MICHAEL JORDAN |

You can also convert to:
- **Lowercase** → `john doe`
- **Proper Case** → `John Doe`

---

## 🔢 Reformatting Numbers

| Raw ID     | Formatted ID |
|------------|---------------|
| 123456789  | 123-45-6789   |
| 987654321  | 987-65-4321   |

Flash Fill detects patterns like SSN formats, phone numbers, etc.

---

## 🆔 Extracting from Codes

| Transaction ID   | Prefix      | Suffix |
|------------------|-------------|--------|
| 40498LYMRD-3989  | 40498LYMRD  | 3989   |
| 40182BYWHJ-3481  | 40182BYWHJ  | 3481   |

Split using Flash Fill:
- Type prefix from first row → Ctrl + E
- Type suffix from first row → Ctrl + E

---

## 💡 Tips

- Flash Fill doesn't update dynamically—it's not a formula.
- Make sure patterns are consistent for better accuracy.
- Works best when data is clean and well-aligned.

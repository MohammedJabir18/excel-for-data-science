# Understanding Cells, Rows, Columns, and Ranges

## 1. Basic Definitions

### Cells
- The smallest unit in a spreadsheet
- Intersection of a row and column
- Address format: `ColumnLetterRowNumber` (e.g., `A1`, `B3`)
- Can contain: values, formulas, text, dates

### Rows
- Horizontal series of cells
- Identified by numbers (1, 2, 3...)
- Maximum rows:
  - Excel: 1,048,576
  - Sheets: 10,000,000

### Columns
- Vertical series of cells
- Identified by letters (A, B, C... then AA, AB, etc.)
- Maximum columns:
  - Excel: 16,384 (XFD)
  - Sheets: 18,278 (ZZZ)

### Ranges
- A selection of multiple cells
- Format: `TopLeftCell:BottomRightCell` (e.g., `A1:D10`)
- Can be contiguous or non-contiguous

## 2. Key Operations

### Cell Operations
| Action | Excel | Google Sheets |
|--------|-------|--------------|
| Select | Click cell | Click cell |
| Edit | F2 or double-click | Double-click |
| Clear | Delete key | Delete key |
| Format | Ctrl+1 | Format menu |

### Row/Column Operations
| Action | Method |
|--------|--------|
| Insert | Right-click row/column number → Insert |
| Delete | Right-click row/column number → Delete |
| Resize | Drag boundary line |
| Hide | Right-click → Hide |

### Range Operations
| Action | Method |
|--------|--------|
| Select | Click+drag or Shift+arrow keys |
| Name | Use Name Box (Excel) or Named Ranges |
| Fill | Drag fill handle (small square at corner) |

## 3. Practical Examples

### Cell References
- Relative: `A1` (changes when copied)
- Absolute: `$A$1` (fixed reference)
- Mixed: `A$1` or `$A1`

### Common Ranges
- Single column: `A:A`
- Single row: `1:1`
- Table block: `B2:F20`
- Non-contiguous: `A1:A10,C1:C10`

## 4. Formatting Guide

### Cell Formatting Options
- Number formats (currency, percentage)
- Font style/size
- Borders and colors
- Text alignment

### Row/Column Formatting
- Height/width adjustment
- Auto-fit to content
- Grouping (Excel) or freezing

## 5. Best Practices

✔ **For Cells:**
- Use clear, consistent data types
- Avoid merging cells when possible
- Add comments for explanations

✔ **For Rows/Columns:**
- Keep headers visible (Freeze Panes)
- Use grouping for large datasets
- Standardize widths/heights

✔ **For Ranges:**
- Name important ranges
- Use table formatting for data blocks
- Avoid selecting entire columns in formulas

## 6. Keyboard Shortcuts

| Action | Excel | Google Sheets |
|--------|-------|--------------|
| Select row | Shift+Space | Shift+Space |
| Select column | Ctrl+Space | Ctrl+Space |
| Select all | Ctrl+A | Ctrl+A |
| Go to cell | F5 | Ctrl+G |
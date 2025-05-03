# Chapter 3: Advanced Formatting Challenges

## Practice Problem: Sales Dashboard Makeover

### Scenario
You've been given a raw sales data spreadsheet that needs to be transformed into a professional, easy-to-read dashboard. Your task is to apply various formatting techniques to make the data more visually appealing and easier to analyze.

### Instructions

1. **Download** the [Sales_Data_Raw.xlsx](/🟢%20Beginner%20Level%20(Foundations)/🎨%20Chapter%203%20-%20Formatting%20Essentials/Practice%20Problems/Sales_Data_Raw.xlsx) file.

2. **Cell Formatting Tasks:**
   - Format the title "Sales Dashboard" in cell A1 using:
     - Font: Arial, 18pt, Bold
     - Fill Color: #4472C4 (dark blue)
     - Font Color: White
     - Add a bottom border: Medium, Black
   - Format the column headers (row 3) using:
     - Bold, Center-aligned
     - Fill Color: #D9E1F2 (light blue)
     - Add all borders: Thin, Black

3. **Conditional Formatting Tasks:**
   - Apply conditional formatting to the "Sales Amount" column:
     - Color Scale: Green-Yellow-Red (Green for highest values, Red for lowest)
   - Apply conditional formatting to the "Profit Margin" column:
     - Icon Sets: 3 Arrows (Green up arrow for values ≥ 30%, Yellow sideways arrow for values between 15-30%, Red down arrow for values < 15%)
   - Apply conditional formatting to the "Status" column:
     - Text contains "Completed": Green fill with dark green text
     - Text contains "Pending": Yellow fill with dark yellow text
     - Text contains "Cancelled": Red fill with dark red text

4. **Number, Date, and Currency Formatting:**
   - Format the "Sales Amount" column as Currency with 2 decimal places
   - Format the "Profit Margin" column as Percentage with 1 decimal place
   - Format the "Transaction Date" column as a custom date format: "mmm d, yyyy" (e.g., "Jan 15, 2023")
   - Format the "Customer ID" column as Text with leading zeros preserved

5. **Worksheet Organization:**
   - Freeze panes at cell A4 (to keep headers visible when scrolling)
   - Group rows by Region (hint: use the Group function)
   - Hide the "Customer ID" column
   - Adjust all columns to autofit content

### Bonus Challenge
Create a custom conditional formatting rule that highlights the entire row of the top 3 sales amounts in a light green background.

### Deliverable
Save your formatted workbook as "Sales_Dashboard_Formatted.xlsx" and submit it for review.

---

## Solution Guide

### Cell Formatting
1. **Title Formatting:**
   - Select cell A1
   - Change font to Arial, 18pt, Bold
   - Home tab → Font group → Fill Color: #4472C4
   - Home tab → Font group → Font Color: White
   - Home tab → Font group → Borders dropdown → Bottom Border → Medium, Black

2. **Column Headers:**
   - Select row 3
   - Home tab → Font group → Bold
   - Home tab → Alignment group → Center
   - Home tab → Font group → Fill Color: #D9E1F2
   - Home tab → Font group → Borders dropdown → All Borders

### Conditional Formatting
1. **Sales Amount Color Scale:**
   - Select the Sales Amount column
   - Home tab → Styles group → Conditional Formatting → Color Scales → Green-Yellow-Red
   
2. **Profit Margin Icon Sets:**
   - Select the Profit Margin column
   - Home tab → Styles group → Conditional Formatting → Icon Sets → 3 Arrows
   - Click "Manage Rules" to edit the rule:
     - Set first threshold to 30% (Green up arrow)
     - Set second threshold to 15% (Yellow sideways arrow)
     - Values below 15% will get Red down arrow

3. **Status Column Text-Based Rules:**
   - Select the Status column
   - Home tab → Styles group → Conditional Formatting → New Rule → "Format only cells that contain"
   - Set up three separate rules:
     - Rule 1: Cell Value → contains → "Completed" → Format: Green fill, Dark green text
     - Rule 2: Cell Value → contains → "Pending" → Format: Yellow fill, Dark yellow text
     - Rule 3: Cell Value → contains → "Cancelled" → Format: Red fill, Dark red text

### Number, Date, and Currency Formatting
1. **Sales Amount:**
   - Select the Sales Amount column
   - Home tab → Number group → Currency format
   - Set decimal places to 2

2. **Profit Margin:**
   - Select the Profit Margin column
   - Home tab → Number group → Percentage format
   - Set decimal places to 1

3. **Transaction Date:**
   - Select the Transaction Date column
   - Home tab → Number group → More Number Formats
   - Select "Custom" category
   - Type "mmm d, yyyy" in the Type field

4. **Customer ID:**
   - Select the Customer ID column
   - Home tab → Number group → Text format

### Worksheet Organization
1. **Freeze Panes:**
   - Click on cell A4
   - View tab → Window group → Freeze Panes → Freeze Panes

2. **Group Rows by Region:**
   - Select the data range
   - Data tab → Outline group → Group → Auto Outline
   - Or manually select rows with the same region and group them

3. **Hide Customer ID Column:**
   - Right-click on the Customer ID column header
   - Select "Hide"

4. **Autofit Columns:**
   - Select all columns with data
   - Home tab → Cells group → Format → AutoFit Column Width
   - Or double-click the boundary between column headers

### Bonus Challenge Solution
1. **Top 3 Sales Amounts:**
   - Select the entire data range
   - Home tab → Styles group → Conditional Formatting → New Rule
   - Choose "Use a formula to determine which cells to format"
   - Enter formula: `=AND(RANK(F4,$F$4:$F$100,0)<=3,F4<>"")`
   - Format: Light green fill
   - Click OK

### Tips for Success
- Use keyboard shortcuts to speed up formatting (e.g., Ctrl+1 for Format Cells dialog)
- Preview your dashboard by scrolling through the data to ensure readability
- Test the freeze panes by scrolling down to verify headers remain visible
- Expand and collapse grouped rows to check functionality
- Consider adding a legend explaining the conditional formatting rules

### Common Mistakes to Avoid
- Applying conditional formatting to header rows
- Forgetting to format numbers appropriately before applying conditional formatting
- Not testing how the dashboard looks with larger datasets
- Overusing colors and making the dashboard visually overwhelming

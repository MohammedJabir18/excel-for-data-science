
# Conditional Formatting in Spreadsheets

## Overview
Conditional formatting automatically applies formatting to cells based on specified rules/conditions. It helps visualize data patterns and highlight important information.

## Common Rule Types

### 1. Cell Value Based
```excel
Format cells if...
- Greater than/Less than/Between [value]
- Equal to/Not equal to [value]
```

### 2. Text Based
```excel
Format cells that...
- Contain/Do not contain [text]
- Begin with/End with [text]
```

### 3. Date Based
```excel
Format cells if date is...
- Yesterday/Today/Tomorrow
- In the past/future
- Within last/next 7 days
```

### 4. Top/Bottom Rules
```excel
Format cells that are...
- Top 10 items/bottom 10%
- Above/below average
```

### 5. Data Bars
```excel
Gradient or solid fill bars proportional to cell value
```

### 6. Color Scales
```excel
2-color or 3-color gradient based on value range
```

### 7. Icon Sets
```excel
Add icons (arrows, flags, ratings) based on value thresholds
```

## How to Apply (Excel)
1. Select cells to format  
2. Go to: Home → Conditional Formatting  
3. Choose rule type  
4. Set rule parameters  
5. Select formatting (fill, font, border)  
6. Click OK  

## Advanced Options

### Custom Formulas
```excel
=AND(A1>100,A1<200)  // Format if between 100-200
=ISBLANK(B1)         // Format blank cells
```

### Managing Rules
- View all rules: Manage Rules  
- Edit/Delete existing rules  
- Change rule priority  
- Stop if true (rule processing order)  

## Examples

### Highlight Duplicates
```excel
Condition: Format cells that contain → duplicate values
Format: Red fill with dark red text
```

### Heat Map
```excel
Condition: Color Scale → Green-Yellow-Red
Applies to: =$B$2:$D$10
```

### Expiry Alerts
```excel
Condition: =AND(A1<TODAY()+30,A1>TODAY())
Format: Yellow fill (expires within 30 days)
```

## Best Practices
- Use subtle formatting for large datasets  
- Combine conditions carefully (avoid conflicts)  
- Document your rules for future reference  
- Consider colorblind-friendly palettes  
- Use named ranges in formulas for readability  

## Limitations
- Maximum of 64 rules per sheet (Excel)  
- Performance impact with large datasets  
- Some rules don't work with filtered data  

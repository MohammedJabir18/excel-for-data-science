# Arithmetic Functions in Excel (SUM, AVERAGE, MIN, MAX)

Excel provides a wide range of built-in arithmetic functions for performing basic mathematical calculations. Four of the most commonly used are **SUM**, **AVERAGE**, **MIN**, and **MAX**.

---

## ➕ SUM

### Purpose
Calculates the total of a range of numbers.

### Syntax
```excel
=SUM(number1, [number2], ...)
```

### Examples
| A   | B   | C   |
|-----|-----|-----|
| 10  | 20  | =SUM(A1:B1) → **30** |
| 15  | 25  | =SUM(A2:B2) → **40** |
| 5   | 35  | =SUM(A3:B3) → **40** |

### Tips
- Use **SUM** instead of **+** for cleaner and faster calculations.  
- Use ranges like **=SUM(A1:A10)** for larger datasets.  
- Combine with **IF** for conditional sums.

---

## ➗ AVERAGE

### Purpose
Calculates the average (arithmetic mean) of a range of numbers.

### Syntax
```excel
=AVERAGE(number1, [number2], ...)
```

### Examples
| A   | B   | C   |
|-----|-----|-----|
| 10  | 20  | =AVERAGE(A1:B1) → **15** |
| 15  | 25  | =AVERAGE(A2:B2) → **20** |
| 5   | 35  | =AVERAGE(A3:B3) → **20** |

### Tips
- Use **AVERAGEIF** for conditional averages.  
- Excludes empty cells from the calculation.

---

## 📉 MIN

### Purpose
Returns the smallest number in a range.

### Syntax
```excel
=MIN(number1, [number2], ...)
```

### Examples
| A   | B   | C   |
|-----|-----|-----|
| 10  | 20  | =MIN(A1:B1) → **10** |
| 15  | 25  | =MIN(A2:B2) → **15** |
| 5   | 35  | =MIN(A3:B3) → **5** |

### Tips
- Use **MINA** to include logical values.  
- Combine with **IF** to find minimums with conditions.

---

## 📈 MAX

### Purpose
Returns the largest number in a range.

### Syntax
```excel
=MAX(number1, [number2], ...)
```

### Examples
| A   | B   | C   |
|-----|-----|-----|
| 10  | 20  | =MAX(A1:B1) → **20** |
| 15  | 25  | =MAX(A2:B2) → **25** |
| 5   | 35  | =MAX(A3:B3) → **35** |

### Tips
- Use **MAXA** to include logical values.  
- Use **MAXIFS** for conditional maximums.

---

## 💡 Tips and Best Practices

- Use **SUM** for totals, not just direct addition.  
- Use **AVERAGE** to quickly find the mean without manual calculations.  
- Use **MIN** and **MAX** for finding ranges in data analysis.  
- Use combinations like **=MAX(A1:A10) - MIN(A1:A10)** to find ranges.  

---

## 📌 Shortcuts

- **Alt + =** - AutoSum (quickly inserts a SUM function)  
- **Ctrl + Shift + T** - Select the entire range for a function  

---

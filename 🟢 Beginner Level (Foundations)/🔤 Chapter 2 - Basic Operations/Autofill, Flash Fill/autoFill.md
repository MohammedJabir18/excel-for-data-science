# Excel AutoFill: Complete Guide

## 1. Basic AutoFill Techniques
- **Drag Fill Handle**: Small square at cell's bottom-right corner
- **Double-Click**: Auto-fill down adjacent columns with data
- **Keyboard Shortcuts**:
  - `Ctrl+D` - Fill Down
  - `Ctrl+R` - Fill Right

## 2. AutoFill by Data Type

### Numbers
| Pattern | Result |
|---------|--------|
| 1, 2 | 3, 4, 5... |
| 5, 10 | 15, 20, 25... |
| 100, 90 | 80, 70, 60... |
| 1.1, 1.2 | 1.3, 1.4, 1.5... |

### Text with Numbers
| Input | Result |
|-------|--------|
| Item1 | Item2, Item3... |
| Q1 | Q2, Q3, Q4... |
| Week1 | Week2, Week3... |

### Dates
| Input | Result |
|-------|--------|
| Jan | Feb, Mar, Apr... |
| Monday | Tuesday, Wednesday... |
| 1-Jan | 2-Jan, 3-Jan... |
| Q1-2023 | Q2-2023, Q3-2023... |

### Times
| Input | Result |
|-------|--------|
| 1:00 AM | 2:00 AM, 3:00 AM... |
| 15 min intervals | 1:00, 1:15, 1:30... |

## 3. Custom Lists

### Built-in Lists
- Days of week (Sunday-Saturday or Monday-Sunday)
- Months (January-December)
- Abbreviated months (Jan-Dec)

### Create Custom Lists
1. File → Options → Advanced → General → Edit Custom Lists
2. Enter items (one per line) or import from cells
3. Click Add → OK

**Example Custom Lists:**
- Departments: HR, Finance, IT, Sales
- Locations: East, West, North, South
- Priority Levels: Low, Medium, High, Critical

## 4. Advanced AutoFill Options

### Fill Options Button (After Dragging)
| Icon | Option | Description |
|------|--------|-------------|
| 📋 | Copy Cells | Duplicates values |
| ↗ | Fill Series | Continues pattern |
| ☀ | Fill Formatting Only | Copies formatting |
| ✏ | Fill Without Formatting | Values only |
| 📅 | Fill Days/Weekdays/Months | Date variations |

### Special Patterns
- **Growth Series**: 2, 4, 8, 16... (Right-click drag → Series → Growth)
- **Linear Series**: 5, 10, 15... (Right-click drag → Series → Linear)
- **Date Units**: Days, Weekdays, Months, Years

## 5. Pro Tips & Tricks

1. **Quick Number Series**:
   - Enter first two values to establish pattern
   - Select both → Drag fill handle

2. **Alternate Patterns**:
   - Hold `Ctrl` while dragging to force copy instead of series

3. **Flash Fill** (`Ctrl+E`):
   - Automatically detects patterns in your data
   - Example: Separate first/last names

4. **Custom Increments**:
   - Right-click drag → Series → Set step value

5. **Repeating Patterns**:
   - Create pattern like A, B, C → Select all three → Drag

## 6. Troubleshooting

**Common Issues:**
- Not recognizing pattern? Enter more examples
- Dates not incrementing? Check cell formatting
- Custom list not working? Verify list exists in options
- Fill handle missing? Enable in Options → Advanced → "Enable fill handle"

> **Note**: AutoFill works similarly in Google Sheets with slightly different menu locations for custom lists.
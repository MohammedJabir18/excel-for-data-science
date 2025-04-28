# Cell Formatting: Fonts, Colors, and Borders

## Font Formatting
Controls the appearance of text within cells.

**Common Font Options:**
- **Font Face:** Change text style (Arial, Calibri, Times New Roman)
- **Font Size:** Adjust text size (8pt, 12pt, etc.)
- **Font Style:** 
  - `Bold` (`Ctrl+B`)
  - *Italic* (`Ctrl+I`)
  - <u>Underline</u> (`Ctrl+U`)
  - ~~Strikethrough~~
- **Text Color:** Change font color
- **Effects:** Subscript, Superscript

## Cell Colors
Modify cell background appearance.

**Options:**
- **Fill Color:** Background color of cells
- **Gradient Fill:** Color transitions
- **Pattern Fill:** Textured backgrounds
- **Transparency:** Adjust opacity level

**Usage:**
1. Select cells
2. Open Format Cells dialog (`Ctrl+1`)
3. Navigate to Fill tab
4. Choose color/pattern

## Borders
Add lines around cells or ranges.

**Border Types:**
| Style | Example |
|-------|---------|
| None |  |
| Thin | ─── |
| Thick | ━━━ |
| Double | ═══ |
| Dotted | ┄┄┄ |
| Dashed | ┈┈┈ |

**Border Placement:**
- Outline (external borders)
- Inside (gridlines between cells)
- Individual sides (top, bottom, left, right)
- Diagonal borders

**Customization Options:**
- Line style (solid, dashed, dotted)
- Line thickness (hairline to thick)
- Line color

## Merge Cells
Combine multiple cells into one.

**Merge Options:**
1. **Merge & Center**  
   - Combines cells and centers content
   - Shortcut: `Alt+H,M,C` (Excel)
   
2. **Merge Across**  
   - Merges rows in selected columns

3. **Merge Cells**  
   - Combines without centering

4. **Unmerge Cells**  
   - Reverts merged cells to original state

**Important Notes:**
- Only upper-left cell data is preserved when merging
- Merged cells can affect sorting/filtering operations
- Avoid excessive merging in data tables

## Text Wrapping
- **Wrap Text:** 
  - Displays long text in multiple lines within cell
  - Auto-adjusts row height
- **Clip Text:** (Default) Hides overflow text
- **Shrink to Fit:** Reduces font size to fit cell
- **Manual Line Breaks:** Insert with `Alt+Enter` (Windows) or `Option+Enter` (Mac)

## Text Orientation
- **Angle:** Rotate text (-90° to +90°)
- **Vertical Text:** Stack characters top-to-bottom
- **Horizontal:** Standard left-to-right
- **Justify Distributed:** Aligns text evenly in cell

## Best Practices
1. Use consistent formatting throughout your spreadsheet
2. Avoid excessive merging as it affects sorting/filtering
3. Use borders sparingly for better readability
4. Ensure text remains readable after rotation
5. Combine formatting with cell styles for efficiency

## Formatting Shortcuts
| Action | Windows Shortcut | Mac Shortcut |
|--------|------------------|-------------|
| Format Cells | `Ctrl+1` | `Cmd+1` |
| Bold | `Ctrl+B` | `Cmd+B` |
| Italic | `Ctrl+I` | `Cmd+I` |
| Underline | `Ctrl+U` | `Cmd+U` |
| Wrap Text | `Alt+H+W` | `Ctrl+Option+W` |
| Merge & Center | `Alt+H+M+C` | `Ctrl+Option+M` |then `Ctrl+Shift+V`)
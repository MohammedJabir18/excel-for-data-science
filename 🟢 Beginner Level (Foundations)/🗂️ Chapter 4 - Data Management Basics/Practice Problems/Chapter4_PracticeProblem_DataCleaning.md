# Chapter 4 Practice Problem: Data Cleaning Exercises for Student Record Manager

## Practice Problem
You are tasked with cleaning a dataset containing student enrollment records for a university. The dataset has inconsistencies, duplicates, and formatting issues that need to be addressed to ensure data integrity. Using Excel's data management tools, perform the following tasks:
1. Sort the data by `Last Name` in ascending order, then by `First Name` in ascending order.
2. Create dropdown lists for the `Department` and `Enrollment Status` columns to ensure consistent data entry.
3. Replace all instances of "CS" with "Computer Science" in the `Department` column.
4. Identify and remove duplicate student records based on the `Last Name` column.

### Dataset
The dataset is provided in an Excel table named `EnrollmentRecords` with the following columns:
- `Student ID` (e.g., STU001, STU002)
- `First Name`
- `Last Name`
- `Department` (e.g., CS, Biology, Math)
- `Enrollment Status` (e.g., Full-Time, Part-Time)
- `Email`

**Sample Data (with issues)**:
<img src="/🟢 Beginner Level (Foundations)/🗂️ Chapter 4 - Data Management Basics/Practice Problems/images/og_dataset.png" width='600'></img>


### Tasks
1. **Sorting**: Sort the dataset by `Last Name` (A-Z) and then by `First Name` (A-Z).
2. **Data Validation**: Create dropdown lists for:
   - `Department`: Options are Computer Science, Biology, Mathematics, Physics.
   - `Enrollment Status`: Options are Full-Time, Part-Time.
3. **Find & Replace**: Replace all instances of "CS" with "Computer Science" in the `Department` column.
4. **Remove Duplicates**: Remove duplicate records based on the `Last Name` column, keeping the first occurrence.

## Solution: Step-by-Step Guide

### Prerequisites
- Microsoft Excel (2016 or later recommended)
- The dataset provided above, entered into an Excel table named `EnrollmentRecords`

### Step-by-Step Solution

#### 1. **Sort the Data**
- Select any cell within the `EnrollmentRecords` table.
- Go to **Data** > **Sort**.
- In the Sort dialog box:
  - Add a sort level for `Last Name`, Sort On: **Values**, Order: **A to Z**.
  - Add another level for `First Name`, Sort On: **Values**, Order: **A to Z**.
- Click **OK** to apply the sort.
- **Result**: The table is sorted with records like `Adams, Mike` appearing before `Brown, Anna`, and `Brown, Sarah`.

#### 2. **Create Dropdown Lists Using Data Validation**
- **Department Dropdown**:
  - Create a new sheet named `Lists`.
  - In `Lists!A1:A4`, enter: `Computer Science`, `Biology`, `Mathematics`, `Physics`.
  - Select the cells under the `Department` column (e.g., D2:D100).
  - Go to **Data** > **Data Validation**.
  - Set **Allow** to **List** and set the source to `=Lists!$A$1:$A$4`.
  - Ensure **In-cell dropdown** is checked and click **OK**.
- **Enrollment Status Dropdown**:
  - In `Lists!B1:B2`, enter: `Full-Time`, `Part-Time`.
  - Select the cells under the `Enrollment Status` column (e.g., E2:E100).
  - Go to **Data** > **Data Validation**.
  - Set **Allow** to **List** and set the source to `=Lists!$B$1:$B$2`.
  - Ensure **In-cell dropdown** is checked and click **OK**.
- **Verification**: Click on cells in the `Department` and `Enrollment Status` columns to confirm dropdown menus appear with the specified options.

#### 3. **Find & Replace**
- Select the `Department` column (e.g., D1:D100, including the header).
- Go to **Home** > **Find & Select** > **Replace**.
- In the **Find what** box, enter `CS`.
- In the **Replace with** box, enter `Computer Science`.
- Click **Replace All**.
- **Result**: All instances of "CS" are replaced with "Computer Science". For example, `STU001` now shows `Computer Science` instead of `CS`.

#### 4. **Remove Duplicates**
- Select any cell within the `EnrollmentRecords` table.
- Go to **Data** > **Remove Duplicates**.
- In the Remove Duplicates dialog box, check only the `Last Name` column to identify duplicates based on this field.
- Click **OK**.
- **Result**: The duplicate record for `Addams` (e.g., the second occurrence) is removed, keeping the first instance.

### Expected Output
After completing the tasks, the cleaned `EnrollmentRecords` table should look like this (sorted and cleaned):
<img src="/🟢 Beginner Level (Foundations)/🗂️ Chapter 4 - Data Management Basics/Practice Problems/images/out_dataset.png" width='600'></img>

- The table is sorted by `Last Name` and then `First Name`.
- Dropdowns are implemented for `Department` and `Enrollment Status`.
- "CS" is replaced with "Computer Science".
- Duplicate `Last Name` (`Addams`) is removed.

### Verification
- Test the dropdowns by adding a new record to ensure only valid options (`Computer Science`, `Biology`, etc.) are selectable.
- Apply filters (Data > Filter) to confirm sorting and data consistency (e.g., filter `Department` to show only `Computer Science` records).
- Check that no duplicate `Student ID` values remain by using a filter or sorting on the `Last Name` column.

### Tips
- Save your work frequently to avoid data loss.
- Use the **Undo** feature (Ctrl+Z) if a step (e.g., Remove Duplicates) produces unexpected results.
- Ensure the table remains formatted as an Excel Table to maintain dynamic ranges for sorting and filtering.
- Keep the `Lists` sheet updated if new departments or statuses are added.

### Download
To download this Markdown file, copy the content into a text editor and save it as `Chapter4_PracticeProblem_DataCleaning.md`. You can also include this in the GitHub repository alongside the `Student_Record_Manager.xlsx` file for reference.
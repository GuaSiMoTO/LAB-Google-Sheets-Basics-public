# LAB-Google-Sheets-Basics
![](https://res.cloudinary.com/dbjlaop5w/image/upload/v1739973806/codeskills/google-sheets/Data%20Management/uwr8pknub6dbgjgx1rkg.png)

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

This lab will guide you through a practical case study to understand and apply fundamental concepts of Google Sheets, including workbook navigation, data entry, formatting, and basic formulas. You will manage data for a small team in an imaginary company.

## Initial Setup

#### Fork The Repository
Now go to GitHub and click the `fork button` to create a copy of this repository in your personal account.

### Iteration 1: Workbook Setup and Exploration
You have been asked to manage a small dataset for your team members in a Google Sheets workbook. Your task involves entering the team members' details, formatting the data for better readability, and ensuring the data is up-to-date.
Before we dive into the details of data entry and manipulation, let's take a moment to set up our workbook and get acquainted with its environment.

1. Open [Google Sheets](https://sheets.google.com) and create a new spreadsheet named 'Introduction_to_Google_Sheets'.
2. Rename the default sheet to 'Employees'.
3. Explore the interface, including menu tabs (File, Edit, View, Insert, Format, Data, Tools, Extensions, Help).

---

### Iteration 2: Data Entry and Table Creation
Let's proceed by creating a table to organize the information of our team members. This table will serve as a comprehensive record for tracking their details effectively.
Enter the following team members' data starting from cell A1:

| Name            | Age | Birthdate  | Email                   | Department | Gross Salary  | Deduction (%) | Start Date | Full-Time |
|-----------------|-----|------------|-------------------------|------------|---------------|---------------|------------|-----------|
| John Doe        | 30  | 01/01/1993 | john.doe@example.com    | Sales      | 55000.00      | 20            | 2015-06-12 | TRUE      |
| Jane Doe        | 28  | 05/15/1995 | jane.doe@example.com    | Marketing  | 52000.00      | 18            | 2016-03-25 | FALSE     |
| Sam Smith       | 35  | 09/22/1988 | sam.smith@example.com   | Finance    | 60000.00      | 22            | 2014-11-10 | TRUE      |
| Alice Lee       | 25  | 12/30/1998 | alice.lee@example.com   | HR         | 48000.00      | 15            | 2017-08-03 | FALSE     |
| Mark Johnson    | 40  | 03/10/1984 | mark.johnson@example.com| IT         | 75000.00      | 25            | 2013-09-18 | TRUE      |

**Add 10 extra rows with fake data.**

After entering the data, ensure that each column is correctly formatted to accommodate the respective data types.
These are the types of data that should be assigned to each column:

1. **Name**: Text
2. **Age**: Number
3. **Birthdate**: Date
4. **Email**: Text
5. **Department**: Text
6. **Gross Salary**: Number (As currency)
7. **Deduction**: Number (As percentage)
8. **Start Date**: Date
9. **Full-Time**: Boolean (TRUE/FALSE)

---

### Iteration 3: Enhancing Data Presentation
Now that we have our table set up, let's make it visually appealing and easier to interpret. We'll add some enhancements to our data presentation to make it more engaging and insightful.

- Tip: Apply bold formatting to the header row, center-align the text, and apply some background color...

---

### Iteration 4: Data Processing and Calculation
Our table looks great now, but let's add some more information to extract insights from it. In this iteration, we'll perform various calculations and data processing tasks to enhance the analysis of our team members' data. Follow these steps to enrich our dataset and derive meaningful conclusions.

1. From the gross salary, create a new column and calculate the net salary based on the gross salary and the deduction to be deducted.
2. Determine and display the oldest and youngest ages using appropriate functions.
3. Count the total number of team members.
4. Calculate the average age and salary of the team members and display it.
5. Calculate the difference between each team member's Gross Salary and the average.
6. Use the `TODAY()` function to display the current date to all members.
7. Calculate the difference in days between the start date of the company and the current day.
8. Create a conditional formula to determine eligibility based on the average age (e.g., "Eligible" if the age is above the average, otherwise "Not Eligible").

**Note**: If you need to create a new column or table to display the results, feel free to do so.

---

### Iteration 5: Leveraging Data Between Sheets
This iteration focuses on leveraging data across multiple sheets within the same Google Sheets workbook, enhancing your ability to organize and analyze information effectively.

You will create a new sheet named "Analysis" to segregate and organize calculated information from the previous iterations, utilizing cell references between sheets.
Transfer the results of calculations, such as net salary, age statistics, and eligibility determination, from the "Employees" sheet to the new "Analysis" sheet using appropriate cell references.

---

### Bonus
To ensure data integrity and accuracy, let's implement additional data validation for the following columns in the "Employees" sheet:

For the "Employees" Sheet:
1. **Age**: Restrict input to values between 18 and 100 to ensure realistic age entries.
2. **Gross Salary**: Allow only positive numeric values to prevent invalid salary entries.
3. **Start Date**: Validate dates to ensure they fall within a reasonable range, such as the last 10 years.

For the "Analysis" Sheet:

1. **Net Salary**: Ensure that the calculated net salary values are non-negative, preventing errors in the analysis.
2. **Age Statistics**: Validate the age statistics to ensure they accurately represent the age distribution of team members.
3. **Eligibility Determination**: Confirm that the eligibility status (e.g., "Eligible" or "Not Eligible") is correctly determined based on the average age criterion.

---

## Submission
Once you have finished, share your Google Sheets file with your instructor and paste here the sharing link:

- **Sharing link:**

Then create a Pull Request!!

## Additional Resources

- [Google Sheets documentation](https://support.google.com/docs/)
- [Conditional Formatting in Google Sheets](https://support.google.com/docs/answer/78413?hl=en)
- [Google Sheets Functions](https://support.google.com/docs/table/25273?hl=en)

![happy_coding](https://res.cloudinary.com/dbjlaop5w/image/upload/v1739973819/codeskills/google-sheets/Data%20Management/qebkyfekuescbozcu8jl.png)

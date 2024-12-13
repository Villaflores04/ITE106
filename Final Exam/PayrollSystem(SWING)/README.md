# Payroll Management System  

A simple payroll management application built with Java Swing. This system enables users to manage employee records, calculate payroll, save data, and display records stored in a file. The program offers an intuitive graphical user interface (GUI) to perform essential tasks such as adding employees, computing salaries, saving data, and presenting payroll information in a tabular format.

## Features  

- **Add Employee**: Input employee details like ID, name, hourly rate, and hours worked.  
- **Calculate Pay**: Compute gross and net pay for an employee based on their hourly rate and work hours.  
- **Save Records**: Store employee payroll details in a file named `payroll.txt`.  
- **Display Records**: Show all saved payroll information in a table format.  
- **Load Existing Records**: Automatically load payroll data from `payroll.txt` when the application launches, if the file exists.  

## How It Works  

### Add Employee  
- Enter details such as `Employee ID`, `Name`, `Hourly Rate`, and `Hours Worked`.  
- The system calculates gross and net pay (after deducting 20% tax) and updates the table with this data.  

### Calculate Pay  
- Input an `Employee ID` to calculate and display the corresponding gross and net pay.  

### Save Records  
- Save all payroll data to a file named `payroll.txt`. The file is created if it does not exist.  

### Display Records  
- View all saved payroll details in a table that includes columns for `Employee ID`, `Name`, `Hourly Rate`, `Hours Worked`, `Gross Pay`, and `Net Pay`.  

### Load Records  
- On startup, the system retrieves existing records from `payroll.txt` (if present) and displays them in the table.  

## File Structure  

- **`PayrollSystem.java`**: The primary Java file containing the application logic.  
- **`payroll.txt`**: A text file for storing payroll records.  
- **`README.md`**: Documentation file.  

## Example Workflow  

1. **Adding an Employee**:  
   - Provide details such as `Employee ID`, `Name`, `Hourly Rate`, and `Hours Worked`, then press the "Add Employee" button.  
   - The system computes pay and adds the record to the table.  

2. **Calculating Pay**:  
   - Enter an `Employee ID` and press "Calculate Pay" to see the computed gross and net pay.  

3. **Saving Records**:  
   - Use the "Save Record" button to store all payroll data in the `payroll.txt` file.  

4. **Displaying Records**:  
   - Click "Display Records" to view all previously saved payroll details in a tabular format.  

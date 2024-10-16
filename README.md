# Code Explanation

# The Python script is designed to perform the following tasks:

# Data Retrieval: Reads employee data from a CSV file using the pandas library.
# Employee Lookup: Searches for a specific employee's details based on their name.
# Salary Processing: Calculates the annual salary for the found employee.
# Data Export: Exports the employee's details to a new CSV file.
# Key Components:

# Import Libraries: The script imports the pandas library for data manipulation.
# Function get_employee_details:
Takes the employee's name and CSV file path as input.
Reads the CSV file into a DataFrame.
Filters the DataFrame to find the employee's details.
Returns the employee's details if found, or a message indicating the employee was not found.
# Function process_salary:
Calculates the annual salary by multiplying the monthly salary by 12.
# Function export_employee_details:
Creates a new CSV file with the employee's details.
# Main Function:
Prompts the user for the employee's name.
Calls the get_employee_details function to retrieve the details.
Processes the salary using the process_salary function.
Exports the employee's details to a new CSV file.

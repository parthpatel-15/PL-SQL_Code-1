# PL-SQL_Code-1
The PL/SQL script includes procedures for salary increment, donor payment information retrieval, and donor filtering. It calculates and updates annual salaries for employees, displays detailed payment information for a specific donor, and filters and displays donor information based on pledge amounts and donor types.

# 4.8 - Salary Increment Procedure:

- Objective:
Calculates and increments the annual salary of employees based on certain conditions.
- Key Components:
Uses a cursor to iterate through employees (excluding presidents) and updates their salaries.
Implements salary increments considering specific conditions.
Displays information about each employee's current and new annual salary.
Calculates the total annual cost of salary increments.
# 4.9 - Donor Payment Information:

- Objective:
Retrieves and displays payment information for a specific donor.
- Key Components:
Utilizes a cursor to fetch details from the dd_payment and dd_pledge tables.
Displays pledge ID, amount, months, payment date, and payment amount for the specified donor.
Prints information in a structured format.
# 4.11 - Donor Filtering:

- Objective:
Filters and displays donor information based on pledge amounts and donor types.
- Key Components:
Defines a cursor to fetch donor and pledge information.
Utilizes a nested loop to apply filtering conditions based on donor type and pledge amount.
Displays donor names and pledge amounts that meet the specified criteria.
# Note:

These PL/SQL snippets are designed for specific scenarios and may need adaptation for different databases.
The README provides an overview, and users should refer to the actual PL/SQL scripts for detailed implementation.

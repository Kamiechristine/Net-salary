## Net Salary Calculator

This is a simple JavaScript function that calculates the net salary of an employee based on their basic salary and benefits. It factors in three main deductions commonly found in Kenya: PAYE (Pay As You Earn) tax, NHIF (National Hospital Insurance Fund) deductions, and NSSF (National Social Security Fund) deductions. The net salary is computed by subtracting these deductions from the gross salary (basic salary + benefits).

## Installation

To use the calculateNetSalary function, simply include it in your JavaScript file or HTML script section. There is no external library required.

## Usage

Function Signature:

function calculateNetSalary(basicSalary, benefits)

## Parameters:

basicSalary (number): The basic salary of the employee.

benefits (number): The additional benefits the employee receives (e.g., allowances).

## Example of Usage:

calculateNetSalary(80000, 30000);

This will compute the net salary for an employee with a basic salary of Ksh 80,000 and benefits of Ksh 30,000.

## Functionality
The function calculates:

Gross Salary: The sum of basic salary and benefits.

PAYE: Pay As You Earn tax based on the Kenyan tax brackets.
NHIF: National Hospital Insurance Fund deduction based on the gross salary.
NSSF: National Social Security Fund deduction with Tier 1 and Tier 2 contributions.
Net Salary: The amount remaining after all deductions.
PAYE Tax Brackets (Kenya):
10% for salaries up to Ksh 24,000
25% for salaries between Ksh 24,001 and Ksh 32,333
30% for salaries between Ksh 32,334 and Ksh 500,000
32.5% for salaries between Ksh 500,001 and Ksh 800,000
35% for salaries above Ksh 800,000
## NHIF Deductions (Kenya):
NHIF contributions are based on salary ranges, ranging from Ksh 150 to Ksh 1,700 depending on the employee's gross salary.
NSSF Contributions (Kenya):
Tier 1: 6% of the salary up to Ksh 7,000.
Tier 2: 6% of the salary between Ksh 7,001 and Ksh 36,000.

## Example
Let's consider an employee with the following details:

Basic Salary: Ksh 80,000
Benefits: Ksh 30,000
Running the function:


calculateNetSalary(80000, 30000);
Output:

Gross Salary: Ksh 110000.00
PAYE Deduction: Ksh 25000.00
NHIF Deduction: Ksh 950
NSSF Deduction: Ksh 1800.00
Total Deductions: Ksh 27850.00
Net Salary: Ksh 82150.00
This output indicates that after the deductions (PAYE, NHIF, NSSF), the net salary is Ksh 82,150.





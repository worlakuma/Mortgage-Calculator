# Mortgage-Calculator
This Python script calculates the scheduled monthly payment and total payment for a loan based on user-provided input such as the principal amount, annual interest rate, and total loan period.

## Input
Principal Amount: Enter the initial loan amount.
Annual Interest Rate: Input the annual interest rate as a percentage.
Total Loan Period in Years: Specify the total duration of the loan in years.

## Output
The script calculates and displays the following:
Scheduled Monthly Payment: The amount of money to be paid monthly towards the loan.
Scheduled Total Payment: The total amount of money to be paid over the entire loan period, including both principal and interest.

## Calculation
The script calculates the scheduled monthly payment (m) and total payment (total_loan_payable) using the following formulas:
Monthly interest rate (r) is calculated by dividing the annual interest rate by 12 months and converting it to a decimal.
Loan period in months (n) is calculated by multiplying the total loan period in years by 12.
The scheduled monthly loan repayment amount (m) is calculated using the formula for an amortizing loan.
The scheduled total loan interest and principal payable (total_loan_payable) is calculated by multiplying the scheduled monthly payment by the total number of months.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
https://github.com/worlakuma/Mortgage-Calculator/blob/main/LICENSE
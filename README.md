# Customer Banking System

## Overview
The Customer Banking System is a Python program that calculates and tracks interest earned on savings and CD accounts. Users input account details like balance, annual interest rate, and months to see interest earned and updated balances.

## Features
- Savings Account:
  - Calculate interest earned.
  - Update the balance with interest.

- CD Account:
  - Same as savings account.

## Getting Started
1. Clone the repository to your computer.
2. Ensure Python 3 or higher is installed.
3. Run `customer_banking.py` to start.

## File Structure
- **account.py**: Defines the `Account` class to manage balances and interest.
- **savings_account.py**: Handles savings account calculations.
- **cd_account.py**: Handles CD account calculations.
- **customer_banking.py**: Main program for user interaction.

## Usage
1. Execute `customer_banking.py`.
2. Input details for the savings account:
   - Balance
   - Annual interest rate
   - Months
3. View the interest and updated balance.
4. Input details for the CD account:
   - Balance
   - Annual interest rate
   - Months
5. View the interest and updated balance.
6. Exit.

## Calculation Formula
interest = balance * (annual interest rate / 100) * (months / 12)


Interest is added to the balance for the updated total.

## License
For educational use only.




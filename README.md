# Customer Banking Module Challenge 3
## Project Overview :
<p> The Customer Banking project is designed to use Classes to set the balance of the customer's savings and CD account.  The user is prompted to enter their savings and CD account balance, interest rate, and the length of months to determine the interest gained. The values the user enters are passed to functions  that are used to calculate the interest earned on the savings and CD accounts and then calculate the updated balance for both accounts. The function returns the updated savings account balance, CD balance, and respective interest rates for both accounts back to the main function and then displays the interest earned on the savings and CD accounts and updates the balances.</p>

## Features of the project :
<p>This project uses classes, functions, and methods to calculate the customer's interest on their savings and CD accounts.</p>	

## Requirements :

> Installations/packages - Anaconda version 24.7.1, Python 3.10 

## Usage :
<p>To use this program you must execute the customer_banking.py file.  This file calls the main function which prompts the user to enter their savings and cd account balance, interest rate, and the length of months to determine the interest earned on each account. It then displays the interest earned on the savings and CD accounts and updates the balances on both accounts.</p>

## Project Structure / Files  :
<p>
<ul>
<li>customer_banking.py - Contains the main function that executes the program.</li>
<li>savings_account.py - Contains the create_savings_account function which creates the saving account, calculates the interest earned, and updates the account balance.</li>
<li>cd_account.py - Contains the create_cd_acount function which creates the cd account, calculates the interest earned, and updates the cd account balance.</li>
<li>account.py - Contains the account class and the set_balance and set_interest functions.</li>
</ul>
</p>

## Code Explanation :
<p>The program will prompt the user to enter their savings and CD account balances, the interest rate they are earning on the account, and the length of months they have been earning interest.  The program will then
calculate the interest earned on both accounts and add the earned interest to the initial balance.  The users' updated balance for their savings and CD accounts is then presented to them using the print function.</p>
<p>The functions used to calculate the savings account interest and the CD account interest are in separate .py files. Additionally, the Account Class is imported into the savings_account and cd_account .py files and the customer_banking file imports the cd_account and savings_account classes from the savings_account and cd_account .py files respectively.</p>

## Troubleshooting :
<p>1. Utilize breakpoints and the print function to determine what the program is doing at various stages in the code.
<p>2. In the savings_account.py and the cd_account.py file, you need to set the initial value of the interest to zero. Do not use the "interest_rate" variable name to initiate the value to zero.
This will result in interested earned value always returning zero.  Create a new variable called apr set this variable to zero and pass the apr variable to the instance of the Account class you create.</p>

## Conclusion :
<p>This program leverages the organizational method of separating functions, classes/methods into separate Python files. In software engineering, Don’t Repeat Yourself (DRY) is a principle of software development
that we can use functions and modules to avoid repeating code.</p>

## Acknowledgments / Resources :
<p>I would like to extend a special thank you to my tutor Dinnara Hitt for giving me the extra guidance I needed to understand why the name and order of variables were important when used in functions.</p>

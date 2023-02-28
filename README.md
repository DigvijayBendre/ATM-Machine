# ATM-Machine   in c++ 
![Web capture_28-1-2022_162059_multiple-disease-predictor1 herokuapp com](https://i.ytimg.com/vi/PgGvLkm8ecs/maxresdefault.jpg)

## About project:
The ATM Management System project is used to do the following actions:  
1. Check balance in their account 
2. Withdraw money. 
3. Deposit money into their bank account
4. Transfer money from one bank account to another bank account.
 
Whenever the user needs to perform any of the above action he/she needs to enter their PIN number (personal identification number) provided by the bank when they have received their ATM card and it will do the required action. We have also provided option for customers to choose between the languages.

## Features to be added in project
1. Features:
2. Select language
3. Check balance
4. Transaction(withdrawal)
5. Deposit
6. Transfer
7. Balance enquiry
8. Exit
 
Detailed project description of the project (can be finalized after implementation of the idea)
The detailed code description of our project is given as follows:

Welcome Message is given to user using default constructor in class atm.
Giving “select Language” option to user to avoid language barrier.(English, Hindi, Marathi)
Checking whether entered key is correct.
If keypin incorrect 3 times, system blocks so that misuse is avoided.
When keypin is correct, following options are provided using method transaction():

## CHECK BALANCE:
In this, account balance is displayed.

## MONEY WITHDRAWL:
Amount of money to be withdrawn is taken from the user. Then if withdrawal amount is less than balance then only money can be withdrawn else message of withdrawal amount greater than bank balance will be displayed.

## DEPOSIT:
In this deposit amount is taken from user and is added to the bank balance. The final bank balance is then displayed.

## TRANSFER:
Here, firstly a 10 digit account number is taken from user to which money is to be transferred. If 3 times entered account is not 10 digit, system blocks. If correct account number, amount of money to be transferred is entered. Then this amount is deducted from bank balance and the final bank balance is shown.

## EXIT:
After done with using the required options, user can exit.
This way user can easily use the bank options.

## Concepts used in the project
Class
Object
Constructor (default)
Pointers
Inheritance (Single, Multiple)
Operators
Polymorphism
Switch statements
If-Else
Looping structures

## Algorithm for the problem statement
Welcome message Display.
Login, enter pin.
If pin correct go to step 3.
Else if pin incorrect provide chance 3 times using loops
If still pin incorrect
Display warning of system block . contact bank  (3 times incorrect)
goto stop.
Login successful
Enter choice
Apply switch statement for each choice
Calling time function after each successful transaction
Displaying menu choice again
If choice= 5
return 0 and STOP


# Budget-App

Budget.py
The code starts with the class definition. The __init__ function is called when a new instance of the Ledger class is created. This function creates an empty list, which will be used to store transactions that have been made by this ledger object. The check_funds function checks if there are enough funds in the account to make a transaction, and returns True or False accordingly. If there are not enough funds, then it returns False so that no transaction can be made at all. The deposit function adds money into the account and stores it as part of its description string for later use in withdraw . It also increments self's amount variable by adding the given amount .

The code is an example of a class that represents the bank account. The __init__ function initializes the bank account with the category parameter, which is passed in by the user. The check_funds function checks if there are funds left in the account and returns true or false accordingly. The deposit function adds money to the account and return true or false depending on whether there are funds left in the account or not. The withdraw function subtracts money from your bank account and returns true or false according to whether there are funds left in your bank account.

The code is a function that returns the balance of an account. The code starts by declaring two variables, amount and description. It then declares a variable called transaction which is used to store information about each transaction in the ledger. result="" result+="*************Food*************"+"\n" The first line creates a string with no content, so it will be empty when printed out later on. The second line adds some text to the string that says "******Food *****". Then it prints out all transactions from the ledger one at a time using for loop.

The code will print out a balance of the account. The __str__() function is used to print out the value of the object in string format.

The code creates a list of categories and then creates a spend chart for each category. The code starts by creating an empty list called categories. Then it iterates through the list, adding one item to the end of the list with "spend" as its name. The next line is where we create our first category: "food". This is done by using Python's built-in function str() which takes in any string and returns that string in lowercase letters. We use this function because we want to make sure that all of our categories are lowercase letters so they can be easily compared later on when we print them out on screen or write them down in a notebook. Next, we add two items to the end of the food category: "groceries" and "restaurants." These are both strings that will be returned from str(). Next, we create another new category called entertainment which has three items: movies, concerts, and sports events. Finally, at the bottom of our program there is an if statement that checks whether or not funds exist before transferring money into a new spending account (self). If funds do exist then self's amount gets subtracted from itself while self's ledger gets appended with information about
The code will create a spend chart for the given categories. The code above is used to create a spend chart for the given categories.

Main.py 
The code starts by importing the budget module.
The code then creates a new Category called "Food".
Next, it transfers 50 from food to clothing.
Then, it withdraws 25.55 from clothing and 100 from auto.
Finally, the code prints out all three categories' balances before running unit tests automatically with main().
The following is an example of a good answer: This entrypoint file to be used in development.
Start by reading README.md import budget from budget import create_spend_chart from unittest import main ##food category food = budget.Category("Food")
The code is an example of a unit test that can be run automatically in the development environment.

Test.py
The code starts by loading the tests from a test case.
The code then runs the text-based unittest runner on the suite of tests.
It prints out some information about how many passed and failed, as well as what those numbers are for each type of result.
Then it sleeps for one second before printing out a JSON dump of all results that were successful or failures.
The code prints the following: { "passed": test_res.wasSuccessful(), "failures": failures, }

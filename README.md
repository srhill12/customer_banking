# Notes for Customer Banking challenge

## Structure and purpose

This code is designed to function as a customer banking system to allows users to calculate and tracker interest earned on both their savings accounts and CD accounts. They will be prompted for inputs and updates on their respective accounts.

The structure is set up to "modularize" the code to make the main function easier to read by importing the necessary classes from the appropriate folders. Not including this README, there are three main parts to this challenge.

- The Savings Account function imports the Account class from the Account.py folder and is used to create a savings account function that uses balance, interest, and months as arguments, or parameters. After the necessary calculations are made, the updated balance and interest are returned to the function.

- The CD Account function imports the Account class from the Account.py folder and is used to create a CD account function that uses balance, interest, and months as arguments, or parameters. After the necessary calculations are made, the updated balance and interest are returned to the function.

- The Main Function imports the two functions created in both the savings and cd account folders. The user is prompted to enter in the relevant information for calculations and is returned the appropriate values. The main function is called at the end to run the program.

## Code Sources

1. Code used in this challenge was in large part inspired by Module 3.3's Activity 8 Stu_Account_Inheritance.

2. Xpert Learning Assistance on the Bootcamp site was used to analyze snippets of code used in error checking, suggestions, and formatting questions. Specifically I asked if two variables could be assigned to the return values of a function at once, or if there needed to be two separate lines for each variable, respectively.

3. Tutorial/Extra Class session on 3/9/24 questions and clarification on instructions were asked of instructior and TA to ensure that I was on the right path.

## Questions/Concerns for Grader

In the Requirements section of the assignment, there is a bullet point under the Create a Main Function that reads, "Code is written to print out the interest earned and updated savings account balance with interest earned for the given months. **The values are formatted to two decimal places and thousandths.**

I did not understand the instruction because it reads to me that I am being asked two separate things. Thousandths is three decimal places. I was informed that Xpert Learning Assistant has knowledge of our assignments and I posed the instruction to it, and the Xpert was confused as well.


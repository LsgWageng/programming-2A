# programming-2A
an application that can be used for personal budget planning. That should help Siphiwe understand his potential problems much better.

The program has two classes,

1. An abstract class called expenses that contains all the set and get methods.
2. The homeloan class which inherits the expenses class.

Running the program:

1. The user will be prompted for their salary before deductions, how much they spend groceries, travelling, water and electricity and other expenses
2. The user will be asked whether they want to (1) rent or (2) buy a property or exit the program by pressing any key
3. If the chose option (1) they will be promted for the monthly rent and the program will then display the sample output
4. If the they chose option (2) they will be prompted to enter the price of the property, interest charged, number of months between 240 and 360 and other expenses related
**NOTE**
if a third of your salary is less than monthly repayment, the program will alert you 

5. After all the expenses have been inputted, the program will calculate and display the folowing sample output below
SAMPLE OUTPUT

BUDGET CALCULATOR
***************************************************
tax :					0.45
groceries :				R2500
water and electricity :			R5000
travelling :				R1000
phone bill :				R780
other expenses :			R890								
property price:				R340
deposite amount:			R210
interest charged:			12%
number of months to repay loan:		245
***************************************************
gross income:				R890
***************************************************
monhtly payments:			R470
total repayment:			R340
***************************************************
available money:			R10000
***************************************************

# programming-2A
an application that can be used for personal budget planning. That should help Siphiwe understand his potential problems much better.
 
Using C# and Visual Studio, I designed and implemented a standalone command line application that
fulfils the following requirements:

1. The user shall be able to enter the following values:
  a. Gross monthly income (before deductions).
  b. Estimated monthly tax deducted.
  c. Estimated monthly expenditures in each of the following categories:
    i. Groceries
    ii. Water and lights
    iii. Travel costs (including petrol)
    iv. Cell phone and telephone
    v. Other expenses
2. The user shall be able to choose between renting accommodation or buying a property.
3. If the user selects to rent, the user shall be able to enter the monthly rental amount.
4. If the user selects to buy a property, the user shall be required to enter the following
   values for a home loan:
    a. Purchase price of property
    b. Total deposit
    c. Interest rate (percentage)
    d. Number of months to repay (between 240 and 360)
5. The software shall calculate the monthly home loan repayment for buying a property
   based on the values that the user entered. 
6. If the monthly home loan repayment is more than a third of the user’s gross monthly
   income, the software shall alert the user that approval of the home loan is unlikely.
7. The software shall calculate the available monthly money after all the specified deductions
   have been made.
8. The software shall not persist the user data between runs. The data shall only be stored in
   memory while the software is running.

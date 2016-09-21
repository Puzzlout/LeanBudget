# Budget sheets

A budget sheet contains:
- A name of the parent budget
- A balance of the parent budget
- One column per account that contains funds assigned to the parent budget
- One line per transaction
  - Note: a same transaction can affect several account (ex: Groceries)

# Add a single-budget transaction 

The form must contain:
- A date field accepting the format:
  - YYYY-MM-DD. ex: 2016-09-21
  - DD-MM with the automatic pick of the current year. ex: 21-09 becomes 21-09-2016 if current year is 2016
  - DD/MM/YYYY or MM/DD/YYYY depending on the local of the user
- A budget
  - selection is made from a auto-complete list
  - it must allow to add automatically a new budget if no item is selected in the auto-complete list.
  - it would be good to prevent insertion of duplicates
- A Payee 
  - selection is made from a auto-complete list
  - it must allow to add automatically a new payee if no item is selected in the auto-complete list
  - it would be good to prevent insertion of duplicates
- A grid of account based on the budget selection
  - The accounts displayed are those configured to receive or spend funds of the budget
  - The 
- A note about the transaction
- A reconciled checkbox in case the transaction is already paid for (cash, immediate debit card, etc)
- An amount

A button to add a multi-budget transaction is displayed.

# Add a multi-budgets transaction

In the screen "Add a single-budget transaction", a click on the button to add a multi-budget transaction displays at least
Same as above but 

# Add an account 
- add a budget 
- add a user
- login
view transactions 
- create report 

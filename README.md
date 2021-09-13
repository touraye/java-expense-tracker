# Java Expense Tracker

Expense tracker is design for keeping track monetary transactions of income and expense on daily basic. 

## Requirement Analysis 

 In a expense tracker app is possible for a transactions to contain both the income and expense. Each time a transaction either a income or expense is entered in a transactions table a row a create with follow fields: `createdAt` `trans_name` `trans_amount` `trans_type` and with this insertion the various are going to be updated  based on the type of the transaction. 

A income table is going to be updated with a insertion of a transactions type of income like wise for expense. These will make a insertion in each table with the follow fields `id` `amount` and `createdAt` both table have the same fields, the id is going be an auto increment hence the tables themselves are going to be update automatically 

Another update will trigger an increment or a decrement in the income table which is the transaction type of expense. Each time an income transaction happens these make an increment in the current income with the current amount passed in(an update), and expense transaction will also make a deduction of the current income with expense amount passed in (an update).

With the collections of daily transactions is worth making a monthly track of the income and expense. Each transaction will make it's monthly transaction table that will sum up all the transaction in given month. These operation is going to be manually handle for the time being 


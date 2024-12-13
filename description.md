## exMan - The CLI Expense Manager
<!-- project description here -->
    A simple expense manager which can be used from Command Line itself. No need of the slow GUI. It can be used for a variety of tasks such as adding new expense, analysing expenses, etc.

## Basic functions
- To create a new .csv file for storing data:  
    > exMan newCSV "filename e.g. April_2024"
- To set a .csv as origin to store the subsequent data:
    > exMan setOrg "filename e.g. April_2024"  

    If the file with such name does not exist then a new file would be created.
- To add a new expense:
    * Single expense(default): Adds only one expense with *all the details* required.
    > exMan add  
    * Single expense(quick): Adds only one expense with only *name* and *amount*.
    > exMan qadd
    * Multiple expenses(default/quick): Adds the no. of expenses as passed in the argument
    > exMan addmul  
    > exMan qaddmul

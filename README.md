# expense-tracker

This is a proposed solution to the [Expense Tracker challenge](https://roadmap.sh/projects/expense-tracker) from [roadmap.sh](https://roadmap.sh/).

## Features

- Users can add an expense with a description and amount.
- Users can update an expense.
- Users can delete an expense.
- Users can view all expenses.
- Users can view a summary of all expenses.
- Users can view a summary of expenses for a specific month (of current year).

## Prerequisites

- Node.js installed on your system.
- Basic knowledge of command-line usage.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/JuanchiFranco/expense-tracker.git
    ```

    ## Usage

    The list of commands and their expected output is shown below:
    
    ```
        node index.js add --description "Lunch" --amount 20
    ```
    ```
        node index.js add --description "Dinner" --amount 10
    ```
    ```
        node index.js list
    ```
    ```
        node index.js summary
    ```
    ```
        node index.js delete --id 2
    ```
    ```
        node index.js summary
    ```
    ```
        node index.js summary --month 8
    ```
    

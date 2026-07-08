# Data Structure

## Project Title
Budget Tracker

## 1. Main Data Entities / Tables

| Entity / Table | Purpose | Example Records |
|---|---|---|
| Expenses | Stores each expense entered by the user. | Food, Transport, Shopping |
| Budgets | Stores the user's monthly budget amount and spending limit. | July Budget: 10,000 THB |
| Categories | Stores expense categories used to organize spending. | Food, Transport, Education |
| Users | Stores basic user information if a login feature is added later. For the MVP, this can use one demo user. | User001 |

## 2. Field Definition

| Entity | Field Name | Data Type | Required? | Example Value | Validation Rule | Used For Search/Filter? |
|---|---|---|---|---|---|---|
| Expenses | expense_id | Text/ID | Yes | EXP001 | Must be unique | Yes |
| Expenses | title | Text | Yes | Lunch at cafeteria | Cannot be empty | Yes |
| Expenses | amount | Number | Yes | 120 | Must be greater than 0 | Yes |
| Expenses | category | Text/List | Yes | Food | Must select a valid category | Yes |
| Expenses | date | Date | Yes | 2026-07-08 | Must be a valid date | Yes |
| Expenses | description | Text | No | Lunch with friends | Maximum 200 characters | No |
| Expenses | status | Text/List | Yes | Active | Active/Deleted | Yes |
| Budgets | budget_id | Text/ID | Yes | BUD001 | Must be unique | No |
| Budgets | monthly_budget | Number | Yes | 10000 | Must be greater than 0 | No |
| Budgets | month | Text | Yes | July 2026 | Cannot be empty | Yes |
| Budgets | total_spent | Number | Yes | 3500 | Calculated from expense records | No |
| Budgets | remaining_budget | Number | Yes | 6500 | Monthly budget minus total spent | No |
| Categories | category_id | Text/ID | Yes | CAT001 | Must be unique | No |
| Categories | category_name | Text | Yes | Food | Cannot be empty | Yes |
| Users | user_id | Text/ID | Yes | USER001 | Must be unique | No |
| Users | username | Text | Yes | demo_user | Cannot be empty | No |

## 3. Status Values

| Status | Meaning | Who Can Update? |
|---|---|---|
| Active | The expense record is currently available and included in the budget summary. | User |
| Edited | The expense record has been updated by the user. | User |
| Deleted | The expense record was removed and is not included in the budget summary. | User |
| Over Budget | The total spending is higher than the monthly budget. | System |
| Within Budget | The total spending is still within the monthly budget. | System |

## 4. Sample Records

Sample dataset file:

`/data/sample-expenses.csv`

| expense_id | title | amount | category | date | description | status |
|---|---:|---:|---|---|---|---|
| EXP001 | Lunch at Cafeteria | 120 | Food | 2026-07-01 | Lunch with classmates | Active |
| EXP002 | Bus Fare | 30 | Transport | 2026-07-01 | Travel to university | Active |
| EXP003 | Notebook | 85 | Education | 2026-07-02 | Purchased study materials | Active |
| EXP004 | Coffee | 65 | Food | 2026-07-03 | Coffee before class | Active |
| EXP005 | Online Shopping | 450 | Shopping | 2026-07-04 | Bought phone accessories | Edited |

## 5. Data Privacy Note

The Budget Tracker MVP will not collect sensitive personal information such as passwords, bank account numbers, credit card details, national identification numbers, home addresses, or exact financial account balances.

For the prototype and testing stage, the team will use sample or anonymized data. Real names will not be included in the dataset. Each test user can be represented using a simple ID such as USER001 or Demo User. Expense descriptions should not include private information.

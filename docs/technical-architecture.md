# Technical Architecture

## Project Title
Budget Tracker

## 1. Selected Prototype Platform

- Frontend: HTML, CSS, and JavaScript
- Data Storage: Browser Local Storage

## 2. Architecture Decision

The team selected HTML, CSS, JavaScript, and Local Storage because this platform is suitable for the Budget Tracker MVP. It is simple to develop, easy for team members to understand, and does not require a complex backend or database.

Using Local Storage allows the prototype to save expense records directly in the user's browser. This is enough for the main MVP features, such as adding expenses, viewing expense records, editing expenses, deleting expenses, setting a monthly budget, and showing dashboard summaries.

This approach also helps the team complete the prototype within the semester timeline. The system can later be improved by connecting it to a real database such as Firebase or Supabase.

## 3. Main Components

| Component | Description | Tool / Technology | Related Requirement |
|---|---|---|---|
| User Interface | Provides pages and navigation for users to use the Budget Tracker system. | HTML, CSS | FR-01 to FR-08 |
| Dashboard / Summary | Displays total spending, monthly budget, remaining budget, and spending summary. | HTML, CSS, JavaScript | FR-03, FR-04 |
| Data Input Form | Allows users to enter expense title, amount, category, date, and description. | HTML Form, JavaScript | FR-01 |
| Data Storage | Saves expense records and budget data in the browser. | Local Storage, JSON | FR-01, FR-04 |
| Expense Record List | Displays all saved expense records in a list or table. | HTML, JavaScript | FR-02 |
| Search and Filter Module | Allows users to search expenses by keyword, category, or date. | JavaScript | FR-05 |
| Edit Expense Module | Allows users to update incorrect expense information. | HTML Form, JavaScript | FR-06 |
| Delete Expense Module | Allows users to remove incorrect or unnecessary expense records. | JavaScript, Local Storage | FR-07 |
| Confirmation Message | Shows feedback after adding, editing, or deleting an expense. | JavaScript, HTML | FR-08 |

## 4. What Will Be Fully Implemented?

The final prototype will fully implement the following features:

- Add Expense
- View Expense List
- Set Monthly Budget
- Dashboard Summary
- Edit Expense
- Delete Expense
- Confirmation Message
- Save data using Browser Local Storage
- Basic Search by expense title or category
- Basic Filter by category

## 5. What Will Be Simulated?

The following features will be simulated or postponed because they require a more advanced backend system:

- User registration and login
- Multiple user accounts
- Cloud database storage
- Password reset and account security
- AI spending recommendations
- Automatic reminder notifications
- Bank account or payment application connection
- Advanced charts and financial reports

## 6. Final Prototype Risk

The biggest technical risk is managing expense data correctly in Local Storage, especially when users edit or delete records. If the data structure is not handled carefully, the dashboard total and remaining budget may show incorrect values.

The team will reduce this risk by using a clear data structure for expense records, testing Add, Edit, and Delete functions carefully, and recalculating the dashboard summary every time the expense data changes. The team will also prepare sample expense data for testing before the final demonstration.

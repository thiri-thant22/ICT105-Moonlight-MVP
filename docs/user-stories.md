# Lab 04 - User Stories and Acceptance Criteria

## User Story Format
As a [user role], I want to [goal/action], so that [benefit/value].

## User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|---|---|---|---|---|---|---|
| US-01 | User | As a user, I want to view the homepage, so that I can understand the purpose of the application. | FR-01 | Must | **Given** the user opens the app, **when** the homepage loads, **then** the project title, description, and "Get Started" button are displayed. | Homepage screenshot |
| US-02 | User | As a user, I want to add a new expense, so that I can record my daily spending. | FR-03 | Must | **Given** the expense form is completed, **when** the user clicks "Save", **then** the expense is successfully recorded. | Add Expense page |
| US-03 | User | As a user, I want to view all my expenses, so that I can review my spending history. | FR-05 | Must | **Given** expense records exist, **when** the user opens the expense list, **then** all recorded expenses are displayed. | Expense List screenshot |
| US-04 | User | As a user, I want to search or filter my expenses, so that I can quickly find a specific record. | FR-06 | Should | **Given** multiple expense records exist, **when** the user searches by category or date, **then** only matching records are displayed. | Search/Filter demo |
| US-05 | User | As a user, I want to edit or delete an expense, so that I can correct incorrect information. | FR-09 | Should | **Given** an existing expense, **when** the user edits or deletes it, **then** the changes are saved successfully. | Edit/Delete demo |
| US-06 | User | As a user, I want to receive a confirmation message after saving an expense, so that I know my action was successful. | FR-11 | Must | **Given** the expense is saved, **when** the process is complete, **then** a success message is displayed. | Success message screenshot |
| US-07 | User | As a user, I want to view a dashboard, so that I can understand my spending habits. | FR-12 | Must | **Given** expense records are available, **when** the user opens the dashboard, **then** total expenses, categories, and remaining budget are displayed. | Dashboard screenshot |
| US-08 | Admin | As an admin, I want to manage expense records, so that incorrect or duplicate data can be removed. | FR-09 | Could | **Given** the admin is logged in, **when** the admin edits or deletes a record, **then** the changes are updated successfully. | Admin page screenshot |

## Acceptance Criteria Checklist

A good acceptance criterion should be:
- Be testable.
- Be observable in the final prototype.
- Be connected to a functional requirement.
- Be supported by customer discovery evidence.
- Be clear and specific.

## Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
|---|---|---|
| US-09 | AI spending recommendations require more development time and data. | Add after the MVP is completed. |
| US-10 | Budget reminder notifications are not essential for the first prototype. | Add in a future version after user validation. |
| US-11 | User account registration and login increase development complexity. | Implement if authentication is required later. |

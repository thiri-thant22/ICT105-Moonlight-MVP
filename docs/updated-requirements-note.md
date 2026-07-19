# Updated Requirements Note

## Purpose
Use this file only if Lab 09 review requires a change to system-requirements.md.

| Requirement ID | Original Requirement | Proposed Update | Reason for Change | Supporting Evidence | GitHub Issue/Commit | Approved by Team? |
|---|---|---|---|---|---|---|
| FR-02 | Users can add income and expense records. | Add input validation to prevent invalid or duplicate transactions. | Improve data quality and reduce user errors. | Lab 09 Risk Register (R-05) | Issue #13 | Yes |
| FR-03 | Users can view transaction records. | Restrict access so only authorized users can view their own financial records. | Protect users' personal financial information. | Lab 09 Risk Register (R-01) | Issue #09 | Yes |
| FR-04 | Users can view the dashboard summary. | Add a disclaimer stating that the dashboard is for personal budgeting only and not financial advice. | Prevent misunderstanding of budget information. | Lab 09 Risk Register (R-04) | Issue #12 | Yes |
| FR-05 | Users can edit and delete transaction records. | Require authentication before editing or deleting transactions. | Improve system security and prevent unauthorized changes. | Lab 09 Risk Register (R-02) | Issue #10 | Yes |
| FR-06 | Users can add transaction notes. | Allow users to edit or remove notes containing personal information. | Protect user privacy. | Lab 09 Risk Register (R-06) | Issue #14 | Yes |

## Rule
Do not silently change system requirements. Every change must be justified, documented, and traceable.

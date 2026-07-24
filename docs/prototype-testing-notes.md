# Prototype Testing Notes

## Test Environment
- Prototype link or folder: prototype/
- Browser/device used: Google Chrome (Windows 11 Laptop)
- Tester role: Student User
- Test date: 24 July 2026

## Main Test Cases

| Test ID | User Flow / Feature | Steps to Test | Expected Result | Actual Result | Status | Issue Found | Fix / Next Action |
|---------|----------------------|---------------|-----------------|---------------|--------|-------------|-------------------|
| T-01 | Open Homepage | Open prototype homepage | Homepage displays correctly with navigation menu | Homepage loaded successfully | Passed | None | No action required |
| T-02 | Submit Expense Record | Fill in expense form and click Save | Expense record is saved to Local Storage | Record saved successfully | Passed | None | Continue testing |
| T-03 | View Expense List | Open Record List page | All saved records are displayed | Records displayed correctly | Passed | None | No action required |
| T-04 | Search / Filter | Search by category or keyword | Matching records are displayed | Search works but category filter needs improvement | Partially Passed | Filter is incomplete | Improve filtering logic |
| T-05 | View Record Details | Select an expense record | Expense details are displayed | Detail page displays correctly | Passed | None | No action required |
| T-06 | Edit / Delete Record | Edit and delete an expense | Record updates or removes successfully | Edit/Delete works correctly | Passed | None | Continue testing |
| T-07 | Dashboard Summary | Open Dashboard | Total income, expenses and balance are shown | Dashboard calculations are correct | Passed | None | No action required |

## Summary of Issues

- Search and category filtering are not fully implemented.
- Responsive layout still needs improvement on small screens.
- More validation messages should be added for invalid inputs.

## Improvements Completed During Lab 11

- Added Local Storage support for expense records.
- Implemented Add Expense and Record List features.
- Improved Dashboard summary calculations.
- Fixed navigation between pages.
- Updated project documentation and README.
- Added testing evidence and screenshots to GitHub.

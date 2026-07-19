# Legal and Ethical Checklist

## Project Title
Budget Tracker Website

## Ethical Review

| Check Item | Yes/No | Evidence / Notes | Mitigation Action | Owner | GitHub Issue/Commit |
|------------|--------|------------------|-------------------|-------|---------------------|
| Users are informed about the purpose of the website. | Yes | The homepage explains that the website helps users record income and expenses. | Keep the description clear and visible. | Team | Lab09 |
| The website avoids misleading claims. | Yes | The website only provides expense tracking and budget summary features. | Review all content before release. | Team | Lab09 |
| The website does not collect unnecessary sensitive data. | Yes | Only username, income, expense, category, and transaction data are used. | Do not collect personal IDs or banking information. | Team | Lab09 |
| Users understand what happens after submission. | Yes | After adding a transaction, the record is saved and displayed on the dashboard. | Display success confirmation messages. | Team | Lab09 |
| Admin functions are separated from normal user actions. | Yes | Only administrators can manage system data, while users manage only their own records. | Apply role-based access control. | Team | Lab09 |
| The website avoids unfair or harmful treatment of users. | Yes | All users receive the same features and equal access to the system. | Continue testing for fairness and accessibility. | Team | Lab09 |

## Summary Decision

**Safe to continue:** **Yes**

**Required revision before implementation:**
- Improve confirmation messages after editing or deleting transactions.
- Add a clearer privacy notice for users.
- Continue improving usability based on customer validation feedback.

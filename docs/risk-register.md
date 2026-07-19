# Risk Register

| Risk ID | Category | Risk Description | Affected Feature / Requirement | Severity | Likelihood | Mitigation Action | Owner | GitHub Evidence | Status |
|---|---|---|---|---|---|---|---|---|---|
| R-01 | Privacy | Unauthorized users may access personal financial records. | User Login, Dashboard (FR-01, FR-03) | High | Medium | Require user authentication and restrict access to each user's own data. | Team | Lab09 | In Progress |
| R-02 | Ethical | Users may misunderstand financial summaries and make poor budgeting decisions. | Dashboard, Reports (FR-03, FR-08) | Medium | Medium | Display clear labels and explanations for charts and reports. | Team | Lab09 | Open |
| R-03 | IP | Icons or templates may be used without proper permission or attribution. | User Interface | Medium | Low | Use free/open-source assets and provide attribution where required. | Team | Lab09 | Closed |
| R-04 | Security | Weak passwords or insecure login may allow unauthorized access. | Login System | High | Medium | Encrypt passwords and validate user authentication. | Team | Lab09 | In Progress |
| R-05 | Legal | The prototype may not fully comply with personal data protection regulations. | User Data Management | Medium | Low | Collect only necessary information and provide a privacy notice. | Team | Lab09 | Open |
| R-06 | Data Quality | Users may enter incorrect income or expense information. | Add Income, Add Expense (FR-01, FR-02) | Medium | Medium | Validate input fields and allow users to edit incorrect records. | Team | Lab09 | In Progress |

## Overall Risk Decision

The Budget Tracker Website is safe to continue developing because no critical risks prevent further implementation. The team has identified privacy, security, legal, ethical, intellectual property, and data quality risks and prepared mitigation actions for each. Before the final implementation, the team should strengthen user authentication, improve data validation, ensure compliance with privacy requirements, and use only properly licensed assets.

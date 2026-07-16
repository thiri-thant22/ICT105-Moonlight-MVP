# ICT105-Moonlight-MVP
# Project Budget Tracker
## Course Information
Course Code: ICT105
Course Name: Fundamental Technology Entrepreneurship
Instructor: Dr. Herison Surbakti
Project Type: 14-Labs Continuous IT Startup MVP Development
## Team Name
Moonlight.
## Team Members and Roles
| Name | Role | Responsibility |
|---|---|---|
| Thiri Sandar | Documentation Lead | maintain documentation |
| Thiri Thant | Technical Lead + UX/UI Lead | Manage repository and Design interface |
| Nang Woo Non | Product Lead + Validation Lead | Define problem, target users, and value proposition |
## Initial Problem Area
Many people cannot manage their expenses properly and often overspend.
## Target Users
People who want to track their daily spending and budget.
## Initial IT Venture Direction
Develop a simple budget tracker app that helps people record and manage expenses easily.
## Technology Possibility
Possible technologies:
- Web application
- Dashboard
- Cloud-based system
- Mobile application
## Repository Structure
- docs: reports, profiles, idea logs, and weekly reflections
- prototype: source code and UI prototype files
- data: survey responses and validation data
- finance: budget planning and financial assumptions
- diagrams: user flow and system design diagrams
- screenshots: evidence of project progress and prototype
- pitch: presentation slides and demo materials
## Weekly Progress Log
| Lab | Main Activity | Output | Status |
|---|---|---|---|
| Lab 1 | Lab setup and idea log | Repository, team profile, initial idea log | In progress |
## Current Status
In Lab1,our team completed the repository setup, assigned team roles, and selected the Budget Tracker project ides. We also identified thee target users and intial problem area.
## Next Step
In Lab2, our team will create the intial UI wireframe, conduct basic user research, and begin developing the prototype structure.
## Initial Problem Area
Many people have difficulty managing their daily expenses and often spend more than their budget. Existing methods are inconvenient or difficult to maintain consistently.
## Target Users
 Students who want to manage their expenses.
 Young professionals who need to track spending and savings.
 Anyone looking for a simple budgeting solution.
## Selected IT Venture Direction
Our team selected to develop a Budget Tracker application. The system will allow users to record expenses, categorize transactions, and monitor their spending habits through an easy-to-use interface.
## Current Status
The team has completed the repository setup, assigned team roles, and finalized the project idea. We also identified the target users and gathered initial requirements for the application.
## Next Step
The next step is to design the Ul wireframe, conduct basic user research, and start developing the prototype structure and core features.

# README Update Template After Lab 03

## Customer Problem Discovery Summary

In Lab 03, our team collected early problem evidence from students and young professionals. The purpose was to confirm whether the problem of expense management is real and important. The interviews showed that many users have difficulty tracking their expenses and often spend more than they planned.

## Target Respondents

We interviewed 10 respondents, including students and young professionals. They are our target users because they regularly manage personal expenses and need a simple way to track their spending and budget.

## Main Evidence Found

The interviews revealed several repeated pain points:

- Most respondents do not record their expenses regularly and rely on memory.
- Many respondents often spend more than their planned budget.
- Current methods such as notebooks, phone notes, and Excel are inconvenient and time-consuming.
- Most respondents do not use a budgeting application and want a simpler solution.

## Updated Problem Statement

Students and young professionals struggle to manage their expenses because they do not record spending regularly and often rely on memory. Existing methods are inconvenient and difficult to maintain, resulting in poor financial awareness and overspending.

## Decision for Next Step

The team decided to continue with the Budget Tracker App idea. Based on the interview evidence, we will focus on creating an MVP with simple expense recording, spending summaries, and budget tracking features that are easy and quick to use.


# Lab 04: User Persona, Requirements, and User Stories

## Primary Target User
The primary target users are university students and young professionals who want a simple and effective way to manage their daily expenses, avoid overspending, and improve their budgeting habits.

### Persona Summary
- **Persona name:** Kelly, 20-year-old University Student
- **User type:** University student who wants to manage daily expenses and stay within budget
- **Main goal:** Record daily expenses and monitor spending easily
- **Main pain point:** Frequently forgets to record expenses and often exceeds the monthly budget
- **Current workaround:** Uses notebooks, mobile notes, spreadsheets, or memory to track expenses

### Key Requirements

| Req ID | Requirement | Priority | Related Evidence |
|---|---|---|---|
| FR-01 | Display a homepage with the project title and main action | Must | Customer Discovery Summary |
| FR-02 | Allow users to navigate through the application | Must | User Persona |
| FR-03 | Allow users to add daily expenses | Must | R001, R003, R005 |
| FR-04 | Store expense records | Must | Customer Discovery Responses |
| FR-05 | Display a list of recorded expenses | Must | R002, R006 |
| FR-06 | Search or filter expenses | Should | R004, R008 |
| FR-07 | View detailed expense information | Should | User Persona |
| FR-08 | Show budget status and remaining budget | Must | Customer Discovery Summary |
| FR-09 | Allow users to edit or delete expense records | Should | R004, R008 |
| FR-10 | Validate required input fields | Must | User Story Evidence |
| FR-11 | Display confirmation messages after user actions | Must | User Story Evidence |
| FR-12 | Display a dashboard with spending summary | Must | Customer Discovery Summary |
| NFR-01 | The application should be simple and easy to use | Must | User Persona |
| NFR-02 | The application should support mobile devices | Must | Target User Analysis |

### MVP Feature Scope

| Feature | Priority | Included in Final Prototype? |
|---|---|---|
| Homepage | Must | Yes |
| Add Expense | Must | Yes |
| View Expense List | Must | Yes |
| Dashboard Summary | Must | Yes |
| Search / Filter Expenses | Should | Yes |
| Edit / Delete Expense | Should | Yes |
| Confirmation Message | Must | Yes |
| User Login | Won't | No |
| AI Spending Recommendation | Won't | No |

### Diagram Links
- **User flow diagram:** `diagrams/user-flow.png`
- **Use case diagram:** `diagrams/use-case-diagram.png`

### GitHub Contribution Evidence
All team members contributed to the project through documentation, requirement analysis, project planning, prototype preparation, GitHub commits, and issue management throughout Lab 04.

# README Update Template - Lab 05


## Lab 05: Product Concept and UI/UX Wireframe

### Product Concept
Budget Tracker is a web-based application designed to help university students manage their daily income and expenses. The website allows users to record transactions, view spending history, monitor their remaining budget, and analyze spending through a dashboard. It helps users develop better financial habits and avoid overspending.

### Requirement-Driven Screens

| Screen | Related Requirement IDs | Wireframe File |
|---|---|---|
| Homepage / Landing | FR-01, FR-02 | /wireframes/homepage.png |
| Input / Submission Form | FR-03, FR-10, FR-11 | /wireframes/input-form.png |
| Records / Information List | FR-05, FR-06 | /wireframes/record-list.png |
| Record Detail View | FR-07, FR-08 | /wireframes/detail-view.png |
| Dashboard / Summary | FR-12 | /wireframes/dashboard.png |
| Admin / Manager View | FR-09, FR-08 | /wireframes/admin-view.png |

### User Flow
Users begin at the Homepage, where they can view their current budget summary. They can add a new income or expense through the Input Form, browse and search transactions in the Records List, view transaction details, edit or delete records if needed, and monitor their financial status using the Dashboard. This user flow supports all core features defined in the MVP.

User Flow Diagram: /diagrams/user-flow.md

### Team Contribution
All team members contributed to the project by analyzing requirements, designing UI/UX wireframes, preparing project documentation, creating the user flow diagram, and updating the shared GitHub repository with their individual commits.

## Lab 07: MVP Experiment Design

### Experiment Objective
Our team will test whether users can easily record expenses, view their spending summary, and navigate the Budget Tracker website without assistance.

### Critical Assumptions
- Users understand the purpose of the Budget Tracker from the homepage.
- Users can successfully record an expense without help.
- Users can easily understand the dashboard summary and navigation.

### MVP Experiment Type
We selected a clickable web prototype with task-based usability testing because it allows us to evaluate whether users can complete the main tasks and provide useful feedback before implementation.

### Success Metrics
- At least 80% of users complete all assigned tasks successfully.
- At least 90% of expense records are submitted correctly.
- At least 80% of users understand the dashboard summary.
- Average usability rating is 4 out of 5 or higher.

### Files Added in Lab 07
- `/docs/mvp-experiment-plan.md`
- `/docs/critical-assumptions.md`
- `/docs/experiment-script.md`
- `/docs/success-metrics.md`
- `/docs/feedback-form.md`
- `/docs/weekly-logbook.md`

### Connection to Final Prototype
The experiment results will help the team improve the user interface, simplify navigation, fix usability problems, and validate the main features before developing the final Budget Tracker prototype.

## Lab 08: Customer Validation and Analytics Sheet

### Validation Objective

The objective of this validation was to evaluate whether the Budget Tracker Website is easy to use and helps university students record and manage their daily expenses effectively. We also collected feedback on usability, navigation, and the dashboard summary.

### Prototype Version Tested

- Version: v1.0
- Link: GitHub Prototype / Figma Prototype
- Screenshots: /screenshots/validation-test-screens.png

### Analytics Summary

| Metric | Result |
|--------|--------|
| Total test users | 20 |
| Task success rate | 80% |
| Average feedback score | 3.5 / 5 |
| Average interest level | 70% |
| Main confusion point | Some users were confused about the Expense Category and Dashboard Summary. |

### MVP Decision

**Continue with minor revisions.**

The validation results show that most users completed the main tasks successfully and found the website useful for tracking their expenses. However, improvements should be made to simplify the dashboard, clarify category labels, and improve navigation.

### Files Added

- `/data/validation-results.xlsx`
- `/data/validation-results.csv`
- `/docs/customer-validation-summary.md`
- `/docs/analytics-insights.md`
- `/docs/mvp-decision.md`
- `/screenshots/validation-test-screens.png`
- `/docs/weekly-logbook.md`

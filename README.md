# OpenCart E-Commerce QA Testing Project

Manual QA testing of a live, self-hosted OpenCart e-commerce application - covering test planning, test case design with requirement traceability, functional, regression, smoke, User Acceptance Test execution, backend data validation via SQL, and defect tracking through JIRA.

**Status:** Ongoing

---

## Application Under Test

| Item | Detail |
|---|---|
| Application | OpenCart v4.1.0.3 |
| Storefront | https://akshaya-qa.infinityfreeapp.com |
| Admin Panel | https://akshaya-qa.infinityfreeapp.com/admin |
| Database | MySQL (table prefix: `ocedb2_`) |
| Hosting | InfinityFree (free tier) |

---

## Objective

To demonstrate a complete, real-world manual QA workflow — from requirement analysis and test design through execution, defect management, and backend validation — against a genuine open-source e-commerce application rather than a static demo site.

---

## What's Covered

- Customer Registration & Login
- Product Search, Browse & Filter
- Shopping Cart (Add / Update / Remove)
- Coupon / Discount Code Application
- Checkout (Guest & Registered)
- Order Confirmation
- Admin Panel — Order & Product Management
- Backend data integrity (SQL validation against MySQL)

---

## Project Workflow

1. **Environment Setup** — Deployed OpenCart on a live hosting environment; diagnosed and resolved a real `open_basedir` deployment error (storage directory misconfiguration) via server logs and file structure correction.
2. **Test Planning** — Authored a formal Test Plan defining scope, approach, environment, entry/exit criteria, and risks.
3. **Test Case Design** — Wrote 35+ manual test cases across 11 requirements, including positive and negative scenarios.
4. **Requirement Traceability Matrix (RTM)** — Mapped every requirement to its covering test case(s) to ensure full coverage.
5. **Backend Validation Checklist** — Prepared SQL queries to confirm UI actions are correctly persisted in the database.
6. **Test Execution** *(in progress)* — Running Smoke, Functional, Regression, Sanity, and UAT cycles against the live application.
7. **Defect Management** *(upcoming)* — Logging and tracking bugs through JIRA's full lifecycle (New → In Progress → Fixed → Retest → Closed), with root cause notes.
8. **Automation** *(planned)* — Automating a subset of stable, high-value test cases using Selenium and PyTest.

---

## Repository Structure

```
opencart-qa-project/
├── README.md
├── Test_Plan.docx
├── QA_Test_Cases_OpenCart.xlsx
│   ├── Read Me
│   ├── Requirements
│   ├── Test Cases
│   ├── RTM
│   ├── SQL Validation
│   └── Summary
├── defect-reports/
│   └── (JIRA bug report screenshots, exported once logged)
├── sql/
│   └── validation_queries.sql
└── automation/
    ├── test_login.py
    ├── test_cart.py
    └── report_generator.py
```

---

## Tools Used

Manual Testing · JIRA · MS Excel · MS Word · MySQL / phpMyAdmin · Git & GitHub · Selenium (planned) · PyTest (planned) · Python / Pandas (planned)

---

## Author

Akshaya — QA Engineer (in progress)


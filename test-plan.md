# Sample Test Plan — Demo E-commerce Web App

> **Portfolio exercise only.** The application, requirements, and defect examples are hypothetical. No live application was tested.

## Objective
Demonstrate how a junior manual QA tester scopes, designs, documents, and reports tests for authentication and shopping-cart functionality.

## Scope
**In scope:** login form validation, successful and unsuccessful login, cart quantity updates, item removal, and cart total calculation.

**Out of scope:** payment processing, production security testing, performance testing, accessibility certification, and API automation.

## Assumed Requirements
- R1: A registered user can log in with valid credentials.
- R2: Invalid credentials produce an informative error without logging the user in.
- R3: Required login fields cannot be submitted empty.
- R4: Users can change cart item quantities to positive integers.
- R5: Removing an item updates the cart.
- R6: Cart subtotal equals the sum of unit price × quantity.

## Test Approach
Manual functional testing, negative-path testing, and basic boundary-value checks.

## Suggested Environment
Desktop Chrome, latest stable version; a non-production test account; sample products with known prices.

## Entry Criteria
Requirements reviewed; test environment and sample accounts available.

## Exit Criteria
Critical test cases executed; observed defects documented; outstanding issues and risks summarized.

## Deliverables
- [Test cases](test-cases.csv)
- [Example bug reports](bug-reports.md)
- [Execution template](test-execution-template.md)

## Important Note
The test cases are designed examples. They have **not been executed** against a real application. Expected outcomes are specifications, not observed results.

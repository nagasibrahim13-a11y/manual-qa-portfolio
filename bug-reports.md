# Sample Bug Reports

> **Hypothetical defects for documentation practice.** These bugs were not observed in a real product and were not filed in Jira.

## BUG-001 — Cart subtotal does not update after quantity increase

- **Type:** Bug
- **Severity:** Major
- **Priority:** High
- **Status:** Example / Not filed
- **Environment:** Hypothetical demo e-commerce app; desktop Chrome
- **Precondition:** Product A is in the cart with unit price 100 TRY and quantity 1.

### Steps to Reproduce
1. Open the cart.
2. Increase Product A quantity from 1 to 2.
3. Observe the displayed subtotal.

**Expected result:** Subtotal changes from 100 TRY to 200 TRY.

**Illustrative actual result:** Quantity changes to 2, but subtotal remains 100 TRY.

**Impact:** Incorrect totals may mislead customers.

**Evidence:** Not available — hypothetical example.

---

## BUG-002 — Invalid credentials produce no visible feedback

- **Type:** Bug
- **Severity:** Minor
- **Priority:** Medium
- **Status:** Example / Not filed
- **Environment:** Hypothetical demo e-commerce app; desktop Chrome
- **Precondition:** A registered test account exists.

### Steps to Reproduce
1. Open the login page.
2. Enter a registered email.
3. Enter an incorrect password.
4. Select **Sign in**.

**Expected result:** A clear error message is displayed; user stays logged out.

**Illustrative actual result:** Login fails silently, with no visible feedback.

**Impact:** Users cannot understand why authentication failed.

**Evidence:** Not available — hypothetical example.

## Jira-style Reporting Checklist
A strong issue report includes a clear summary, environment, reproducible steps, expected vs. actual behavior, severity/priority, and screenshots or logs when available.

# Bug Report - SQA Demo Website

## Bug #1: Login works with any password
**Severity:** Critical
**Priority:** High
**Test Case ID:** TC_002

**Steps to Reproduce:**
1. Go to login section
2. Enter username: admin
3. Enter any password (e.g., "wrong")
4. Click Login button

**Expected Result:** Show "Invalid credentials" error
**Actual Result:** Shows "Login Success"

---

## Bug #2: Addition shows wrong result
**Severity:** High
**Priority:** High
**Test Case ID:** TC_004

**Steps to Reproduce:**
1. Go to calculator section
2. Enter num1: 2
3. Enter num2: 3
4. Click Add button

**Expected Result:** 5
**Actual Result:** "23"

---

## Bug #3: Division by zero shows Infinity
**Severity:** Critical
**Priority:** High
**Test Case ID:** TC_006

**Steps to Reproduce:**
1. Go to calculator section
2. Enter num1: 10
3. Enter num2: 0
4. Click Divide button

**Expected Result:** "Cannot divide by zero"
**Actual Result:** "Infinity"

---

## Bug #4: Negative age shows "Minor"
**Severity:** Medium
**Priority:** Medium
**Test Case ID:** TC_008

**Steps to Reproduce:**
1. Go to age validator section
2. Enter age: -5
3. Click Check button

**Expected Result:** "Invalid age"
**Actual Result:** "Minor"

---

## Bug Summary

| Bug ID | Description | Severity | Status |
|--------|-------------|----------|--------|
| BUG-01 | Login any password | Critical | Open |
| BUG-02 | Addition wrong | High | Open |
| BUG-03 | Divide by zero | Critical | Open |
| BUG-04 | Negative age | Medium | Open |

**Total Bugs Found:** 4
**Critical:** 2 | **High:** 1 | **Medium:** 1
# Test Cases

## 1. Login Functionality

### Test Case 1.1 – Successful Login
**Precondition:** User has a registered account.

**Steps:**
1. Open the login page
2. Enter valid email
3. Enter correct password
4. Click "Login"

**Expected Result:**
User is redirected to the dashboard page.


### Test Case 1.2 – Invalid Password

**Steps:**
1. Open the login page
2. Enter valid email
3. Enter incorrect password
4. Click "Login"

**Expected Result:**
Error message is displayed.
User remains on login page.


---

## 2. Form Submission

### Test Case 2.1 – Required Field Validation

**Steps:**
1. Open form page
2. Leave required field empty
3. Click "Submit"

**Expected Result:**
Validation message appears.
Form is not submitted.

# QA Manual Testing Report

**Project Name:** Student Web Application  
**Application URL:** https://the-internet.herokuapp.com  
**Tester:** Bhagyashree Urunkar  
**Date:** 31 October 2025  
**Environment:** Ubuntu 24.04, Google Chrome  
**Testing Type:** Manual Functional Testing  

---

## 🎯 Objective
To verify the functionality, usability, and UI consistency of the web application https://the-internet.herokuapp.com through manual testing.

---

## ✅ Test Summary

| Result | Count |
|---------|--------|
| PASS | 8 |
| FAIL | 2 |
| TOTAL | 10 |

---

## 🧪 Test Case Execution Details

| Test Case ID | Title | Expected Result | Actual Result | Status | Screenshot |
|---------------|--------|------------------|----------------|----------|-------------|
| TC001 | Valid Login | Redirect to dashboard | Login successful, message displayed | ✅ PASS | screenshots/TC001.png |
| TC002 | Invalid Password | Error message displayed | Error message “Your password is invalid!” displayed | ✅ PASS | screenshots/TC002.png |
| TC003 | Empty Username | Validation error displayed | Username field validation displayed | ✅ PASS | screenshots/TC003.png |
| TC004 | Empty Password | Validation error displayed | Password field validation displayed | ✅ PASS | screenshots/TC004.png |
| TC005 | Logout Functionality | Redirect to login page | Logout successful | ✅ PASS | screenshots/TC005.png |
| TC006 | Dashboard Load | Dashboard loaded properly | All sections displayed | ✅ PASS | screenshots/TC006.png |
| TC007 | Forgot Password | Reset link sent | Confirmation message displayed | ✅ PASS | screenshots/TC007.png |
| TC008 | Invalid Username | Error message displayed | Invalid username message displayed | ✅ PASS | screenshots/TC008.png |
| TC009 | Remember Me Checkbox | Username remembered | Username not remembered | ❌ FAIL | screenshots/TC009.png |
| TC010 | UI Layout Check | Consistent layout across browsers | Misalignment in Firefox | ❌ FAIL | screenshots/TC010.png |

---

## ⚠️ Issues Found
1. **Remember Me Checkbox** — Does not retain username between sessions.  
2. **UI Layout Issue** — Misalignment found in Firefox browser.  

---

## 💡 Recommendations
- Implement cookie/session persistence for “Remember Me”.  
- Perform cross-browser UI testing and fix CSS alignment.  
- Automate regression tests with Selenium + Pytest.

---

## 📎 Attachments
- `manual_test_cases.csv`  
- `screenshots/` folder with all test evidence  

---

**Prepared by:** Bhagyashree Urunkar  
**Date:** 31 October 2025  

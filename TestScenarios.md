# Test Scenarios — TutorialsNinja (Registration & Login)

**Prepared by:** Alka Fathima V B  
**Date:** 23-10-2025

---

## 1. Registration Scenarios

1. Register with valid details.  
2. Register with an already registered email.  
3. Register with invalid email format.  
4. Register with blank mandatory fields.  
5. Register with weak password (if password rules apply).  
6. Register with mismatched confirm password (if present).  
7. Register with long input values (field length limits).  
8. Register with special characters in the name.  
9. Verify privacy/terms checkbox required behavior (if present).  
10. Verify email confirmation message (if applicable).  

---

## 2. Login Scenarios

1. Login with valid email & password.  
2. Login with valid email and wrong password.  
3. Login with unregistered email.  
4. Login with blank fields (email, password, or both).  
5. Password case-sensitivity check.  
6. Error message correctness and clarity.  
7. Session handling: logout and attempt to access protected pages.  
8. Check login UI elements: labels, placeholders, buttons enabled/disabled.  
9. Verify “Forgot Password” link functionality.  
10. Verify login page redirects to correct account/dashboard page after successful login.

---

### Notes

- Each scenario can be converted into **one or more test cases** in `TestCases.xlsx`.  
- Include **positive and negative scenarios** for completeness.  
- Take **screenshots for every executed scenario** and store them in the Screenshots folder.  

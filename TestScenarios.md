# Test Scenarios — TutorialsNinja (Registration & Login)

**Prepared by:** Alka Fathima V B  
**Date:** 23-10-2025

---

## 1. Registration Scenarios

1. Register with valid details.
2. Verify that a confirmation mail is sent to the registered mail id.  
3. Register with an already registered email.  
4. Register with invalid email format.  
5. Register with blank mandatory fields.  
6. Register with weak password (based on password rules).  
7. Register with mismatched confirm password (if present).  
8. Register with long input values (field length limits).   
9. Verify privacy policy checkbox is mandatory for registration (if present).   

---

## 2. Login Scenarios

1. Login with valid email & password.  
2. Login with valid email and wrong password.  
3. Login with unregistered email.  
4. Login with blank fields (email, password, or both).  
5. Login with invalid credentials. 
6. Verify after login it redirect to correct dashboard. 
7. Check login UI elements.  
8. Verify “Forgot Password” link functionality.  
9. Verify Logout process works correctly.

---

### Notes

- Each scenario can be converted into **one or more test cases** in `TestCases.xlsx`.  
- Include **positive and negative scenarios** for completeness.  
- Take **screenshots for every executed scenario** and store them in the `Screenshots` folder.  

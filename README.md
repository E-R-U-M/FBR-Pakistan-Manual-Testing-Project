#  FBR Pakistan – Manual Testing Project

This repository contains manual test cases for the **FBR Pakistan** web application, executed and documented by the QA team. The tests cover a wide range of functional, UI, role-based, and error-handling scenarios across different user roles and modules.

---

##  Project Information

- **Project Name**: FBR Pakistan
- **Module**: Website Functionality Manual Tests
- **Test Designed By**: Erum Ayoub
- **Test Executed By**: Erum Ayoub
- **Test Dates**: 23/10/2022
- **Reviewed By**: Paperfree.pk

---

##  Key Highlights

-  **60+ Detailed Test Cases**
-  Covers **Admin, Revenue Officer, Superintendent, Director**, and **Inspection roles**
-  Includes **Login, Session Timeout, Forgot Password, Validation**
-  Validates **Document Received, Reports, Inbox, and Demand Note modules**
-  Error-handling cases like **500 errors and task assignment failures**
-  Covers UI/UX checks, backend failures, and permission-based access

##  Test Objective

To verify the overall functionality, data validation, user role access, and workflow navigation of the FBR Pakistan web-based application using manual testing methods.

---

##  Module: Website Functionality – Manual Tests

- Validate login/logout functionality  
- Validate multiple user roles and dashboards  
- Test core modules: Document Received, Reports, Demand Notes, Setup, etc.  
- Perform input validation and error handling  
- Forgot Password & Reset Password flows  
- Positive and negative test scenarios  
- UI element verification

---

##  Test Status Summary

| Status       | Count | Percentage |
|--------------|-------|------------|
| ✅ **Pass**   | 54    | 90%        |
| ❌ **Fail**   | 6     | 10%        |
| 🔄 Not Run    | 0     | 0%         |
|Retest Recommended | Yes, for failed cases |

---

## ⚠ Failed Test Cases Summary

| TC No. | Description                           | Reason of Failure                | Suggestion                            |
|--------|---------------------------------------|----------------------------------|----------------------------------------|
| TC04   | Document Received form load/save      | Saving is slow                   | Optimize backend logic                 |
| TC05   | Document Received task assignment     | Task not assigned                | Fix backend assignment logic           |
| TC41   | Add Demand Note                       | Error 500                        | Fix backend API                        |
| TC42   | Edit Demand Note                      | Error 500                        | Resolve PUT/POST logic                 |
| TC44   | Next Action page not loading          | Navigation issue                 | Fix route handling                     |
| TC16   | Unit 12 admin role (potential typo)   | Role functionality unclear       | Clarify and verify access permissions  |

---

##  Types of Testing Performed

| Type                        | Description                                                 |
|-----------------------------|-------------------------------------------------------------|
| Functional Testing          | All modules tested against functional specs                 |
| Manual Testing              | Executed without automation                                 |
| UI Testing                  | Verified buttons, icons, layout, responsiveness             |
| Positive Testing            | Valid inputs, correct flows tested                          |
| Negative Testing            | Invalid inputs, form validation, error prompts              |
| Role-Based Testing          | Multiple dashboards and roles tested                        |
| Regression Testing          | Features rechecked after changes                            |
| Error Handling Testing      | Error messages, system failures (error 500s) observed       |
| Security Testing (basic)    | Login field validations, session handling tested            |

---

---

## Tools Used

-  Manual Test Design (Microsoft Excel)
-  Test Case File exported as PDF
-  Git & GitHub for version control
-  Test created and executed manually on **23/10/2022**

---

## 📁 Repository Structure

```bash
📂 fbr-test-cases/
├── 📄 README.md              # Project overview
├── 📄 LICENSE                # Usage license
└── 📄 FBR_Test_Cases.pdf     # Detailed manual test case document

---

##  Final Result

> **Application Status**:  *Pass with Minor Issues*

Majority of test cases passed successfully. Backend-related failures must be resolved before production deployment.

---

##  Notes

- Testing performed on `https://www.paperfree.pk/fbr/Home`
- Test data is based on the current version as of October 2022.
- Issues related to backend performance, error 500s, and task assignments must be addressed by the development team before the next round of testing.
- Naming consistency and role hierarchy should be clearly documented in the system (e.g., “Chief Inspection Region Deputy” vs. “Additional Unit Twelve”).
- No automation tools were used

- ---

##  Recommendations

- Add automated regression testing for login and document workflows.
- Improve error handling to avoid generic server errors.
- Optimize database saving logic for task assignment modules.

---

##  Contact

For questions or contributions:

**Test Engineer:** Erum Ayoub  
**Company:** [Paperfree.pk](https://www.paperfree.pk)

---


# FBR Pakistan - Website Functionality Test Cases

## Project Information
- **Project Name**: FBR Pakistan
- **Test Date of Creation**: 23/10/2022
- **Test Designed By**: Erum Ayoub
- **Test Executed By**: Erum Ayoub
- **Module**: Website Functionality Manual Tests
- **Test Execute Date**: 23/10/2022
- **Reviewed By**: Paperfree.pk
- **Review Date**: 23/10/2022
- **Final Result**: Pass / Fail

---

## 📋 Test Cases

| TC # | Action (Description) | Input Data | Expected Outcome | Actual Result | Status | Remarks |
|------|----------------------|------------|------------------|---------------|--------|---------|
| TC01 | Launch the application URL and verify that the login page opens correctly | URL: https://www.paperfree.pk/fbr/Home  | The website should load and display the login form with fields for username and password | Login page displayed correctly | Pass | None |
| TC02 | Attempt to log in with valid admin credentials | Username: super.admin<br>Password: "*****" | The system should authenticate the user and redirect them to the Admin Dashboard | Pass | Pass | None |
| TC03 | Verify all tabs and widgets are visible and functional on the Admin Dashboard | Navigate through dashboard sections | All widgets and navigation tabs should be visible and clickable | Displayed correctly | Pass | None |
| TC04 | Click on the Document Received menu option | Sidebar menu items functionality | The Document Received form should open with input fields like Reference Number, Title, etc. | Form loaded successfully | Fail | Saving data is slow and task assignment fails |
| TC05 | Fill in the Document Received form with valid data and attempt to save | Enter valid values in all required fields | The system should save the document details and assign tasks to relevant users | Some data not saved, task not assigned | Fail | Improve backend logic for saving and assigning tasks |
| TC06 | Click on the Document Received Reports icons | Click applied on data print, delete, download, edit and old record | A report view should appear with search, print, and download options | Icons worked correctly | Pass | None |
| TC07 | Use the search functionality within the Document Received Report | Enter a known reference number | The system should filter and display matching records | Search function worked | Pass | None |
| TC08 | Try printing or downloading the Document Received Report | Click print/download buttons | The system should generate a printable or downloadable version of the report | Downloaded successfully | Pass | None |
| TC09 | Navigate to the Input Page and check the Saved Documents section | Go to Input & Saved Documents | Previously saved documents should be listed with options to view or edit | Section displayed correctly | Pass | None |
| TC10 | Recheck the Document Received Reports from the side menu | From the main navigation | The system should display the reports page again with full functionality | Page displayed properly | Pass | None |
| TC11 | Create a new Revenue Officer (RO) account under User Credentials in DAK management system | Enter valid Revenue Officer user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC12 | Create a new Superintendent Officer Grade Four (SO 04) account in DAK management system | Enter valid Superintendent Officer Grade Four user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC13 | Create a new Director Customs Headquarters account (DC HQ) in DAK management system | Enter valid Director Customs Headquarters user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC14 | Create a new Chief Inspection Region account in DAK management system | Enter valid Chief Inspection Region user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC15 | Create a new Chief Inspection Region Deputy account in DAK management system | Enter valid Chief Inspection Region Deputy user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC16 | Create an administration functionality for Credential Unit 12 account in DAK management system | Enter valid Unit 12 user details | The system should create the account and assign related tasks | Account created successfully | Pass | None |
| TC17 | Log out of the admin account | Click the Logout icon | The system should end the session and redirect to the login page | Successfully logged out | Pass | None |
| TC18 | Log in using the newly created Revenue Officer account | Enter Revenue Officer username and password | The system should authenticate and redirect to the Revenue Officer dashboard | Dashboard loaded successfully | Pass | None |
| TC19 | Verify all dashboard elements on the Revenue Officer dashboard | Click on all available icons and tabs | All modules and features should be accessible and functional | All functions working | Pass | None |
| TC20 | Log out from the Revenue Officer account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC21 | Log in using the newly created Superintendent Officer Grade Four account | Enter Superintendent Officer Grade Four username and password | The system should authenticate and redirect to the Superintendent Officer Grade Four dashboard | Dashboard loaded successfully | Pass | None |
| TC22 | Verify all dashboard elements on the Superintendent Officer Grade Four dashboard | Click on all available buttons | All dashboard components should be interactive and display correct data | All functions working | Pass | None |
| TC23 | Log out from the Superintendent Officer Grade Four account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC24 | Log in using the newly created Director Customs Headquarters account | Enter Director Customs Headquarters username and password | The system should authenticate and redirect to the Director Customs Headquarters dashboard | Dashboard loaded successfully | Pass | None |
| TC25 | Verify all dashboard elements on the Director Customs Headquarters dashboard | Explore inbox, document lists, and other sections | All sections should be accessible and display current information | All sections accessible | Pass | None |
| TC26 | Log out from the Director Customs Headquarters account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC27 | Log in using the newly created Chief Inspection Region account | Enter Chief Inspection Region username and password | The system should authenticate and redirect to the Chief Inspection Region dashboard | Dashboard loaded successfully | Pass | None |
| TC28 | Verify all dashboard elements on the Chief Inspection Region dashboard | Check all navigation links | All features should work and allow access to necessary tools | All functions working | Pass | None |
| TC29 | Log out from the Chief Inspection Region account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC30 | Log in using the newly created Chief Inspection Region Deputy account | Enter Chief Inspection Region Deputy username and password | The system should authenticate and redirect to the Chief Inspection Region Deputy dashboard | Dashboard loaded successfully | Pass | None |
| TC31 | Verify all dashboard elements on the Chief Inspection Region Deputy dashboard | Click on all dashboard icons | All features should work and allow access to necessary tools | All functions working | Pass | None |
| TC32 | Log out from the Chief Inspection Region Deputy account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC33 | Log in using the newly created Additional Unit Twelve account | Enter Unit Twelve username and password | The system should authenticate and redirect to the Unit Twelve dashboard | Dashboard loaded successfully | Pass | None |
| TC34 | Verify all dashboard elements on the Additional Unit Twelve dashboard | Explore all available sections | All sections should be visible and fully functional | Sections displayed and working | Pass | None |
| TC35 | Log out from the Additional Unit Twelve account | Click the Logout icon | The system should log out and return to the login screen | Successfully logged out | Pass | None |
| TC36 | Navigate to the Setup Page and click on “Document Source” | From the sidebar menu | The system should display a list of existing document sources and allow adding new ones | List appeared and editable | Pass | None |
| TC37 | Add a new officer rank in the Setup Page | Click on Officer Rank section and add a new entry | The system should allow creating and displaying a new officer rank | Rank added successfully | Pass | None |
| TC38 | Open the Inbox Page from the sidebar menu | Click on Inbox | The system should load the Inbox dashboard showing received messages and actions | Inbox loaded correctly | Pass | None |
| TC39 | Perform actions inside the Inbox such as search, print, and view | Use the search bar and icons | The system should allow filtering, viewing, and exporting inbox items | All actions worked | Pass | None |
| TC40 | Navigate to the Demand Note/Recovery tab | From the appropriate module or menu | The system should open the Demand Note/Recovery tab with relevant fields | Tab loaded correctly | Pass | None |
| TC41 | Attempt to add a new demand note | Fill in the required fields and click Save | The system should either save the note or show an error | Error occurred during saving | Fail | Fix error 500 and allow proper note creation |
| TC42 | Edit an existing demand note | Select a note and modify its content | The system should update the note successfully | Error occurred during editing | Fail | Fix error 500 and allow editing |
| TC43 | View the Demand Note Reports | Click on the reports section | The system should display reports with options to search and print | Reports displayed and functional | Pass | None |
| TC44 | Navigate to the Next Action Page | From the sidebar or another module | The system should load the Next Action page with relevant tasks | Unable to access due to error | Fail | Fix navigation issue |
| TC45 | Log out from the current user session | Click the Logout icon | The system should terminate the session and return to the login screen | Logged out successfully | Pass | None |
| TC46 | Attempt to log in with an incorrect username | Enter wrong username, correct password | The system should display an authentication error message | Error shown correctly | Pass | None |
| TC47 | Attempt to log in with an incorrect password | Enter correct username, wrong password | The system should display an authentication error message | Error shown correctly | Pass | None |
| TC48 | Attempt to log in with both incorrect username and password | Enter invalid values | The system should display an authentication error message | Error shown correctly | Pass | None |
| TC49 | Test case sensitivity in login by entering mixed-case credentials | Username and password with uppercase and lowercase letters | The system should treat credentials as case-sensitive and deny access if mismatched | System handled correctly | Pass | None |
| TC50 | Leave the login form blank and try to submit | Leave both username and password fields empty | The system should display validation errors asking for required fields | Validation errors shown | Pass | None |
| TC51 | Submit login form with only username field filled | Enter valid username, leave password blank | The system should prompt for missing password | Prompted correctly | Pass | None |
| TC52 | Submit login form with only password field filled | Leave username blank, enter valid password | The system should prompt for missing username | Prompted correctly | Pass | None |
| TC53 | Try logging in after session timeout | Wait for idle time to expire session | The system should automatically log the user out and redirect to login page | Automatically logged out | Pass | None |
| TC54 | Click on the Forgot Password link from the login page | On the login screen | The system should open the forgot password recovery page | Recovery page opened | Pass | None |
| TC55 | Enter a valid email address on the Forgot Password page | Email registered with the system | The system should send a password reset link to the provided email | Reset link sent successfully | Pass | None |
| TC56 | Enter an invalid email address on the Forgot Password page | Unregistered or malformed email | The system should show an error indicating the email is not found or invalid | Error message shown | Pass | None |
| TC57 | Leave the email field blank on the Forgot Password page | Do not enter anything on email space | The system should show a validation error asking for an email address | Validation error shown | Pass | None |
| TC58 | Submit the password reset form with non-matching passwords | Enter two different passwords in the new password and confirm password fields | The system should show an error stating that the passwords do not match | Error shown correctly | Pass | None |
| TC59 | Submit the password reset form with a weak password | Enter a short or common password | The system should warn the user about weak password strength | Warning shown | Pass | None |
| TC60 | Submit the password reset form with a strong password | Enter a complex password with mix of characters | The system should accept the new password and update it in the system | Password updated successfully | Pass | None |

---

## 🛠️ Recommendations
- Improve backend logic for saving and assigning tasks.
- Fix error 500 when saving/editing demand notes.
- Ensure navigation to the Next Action page works without issues.
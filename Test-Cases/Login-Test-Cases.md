# Login Page Test Cases

## Project: Login Page Testing

| Test Case ID | Test Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC_01 | Login with valid credentials | Valid username and password | User should login successfully |
| TC_02 | Login with invalid password | Valid username, wrong password | Error message should appear |
| TC_03 | Login with empty username | Empty username, valid password | Validation message should appear |
| TC_04 | Login with empty password | Valid username, empty password | Validation message should appear |
| TC_05 | Login with both fields empty | Both fields empty | Required field messages should appear |
| TC_06 | Verify password masking | Enter password | Password should be masked |

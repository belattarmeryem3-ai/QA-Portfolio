# Bug Reports

# Bug Reports

The following defects are candidates identified during manual testing.
Each defect will be verified against the application before being marked as confirmed.

| Bug ID | Bug Title | Severity | Priority | Environment | Steps to Reproduce | Expected Result | Actual Result | Status |
|--------|-----------|----------|----------|-------------|---------------------|-----------------|---------------|--------|
| BUG_001 | Employee search returns incorrect results | Medium | Medium | Windows 11, Chrome | 1. Log in.<br>2. Open PIM.<br>3. Search for an existing employee. | The correct matching employee should be displayed. | To be verified during test execution. | Candidate |
| BUG_002 | Required field validation is missing when adding an employee | Medium | High | Windows 11, Chrome | 1. Open PIM.<br>2. Click Add.<br>3. Leave required fields empty.<br>4. Click Save. | Appropriate validation messages should be displayed. | To be verified during test execution. | Candidate |
| BUG_003 | Invalid employee data is accepted | Medium | Medium | Windows 11, Chrome | 1. Open Add Employee.<br>2. Enter invalid data in a field.<br>3. Click Save. | Invalid data should be rejected with an appropriate validation message. | To be verified during test execution. | Candidate |
| BUG_004 | Leave request accepts an invalid date range | High | High | Windows 11, Chrome | 1. Open Leave.<br>2. Open Apply Leave.<br>3. Select an invalid date range.<br>4. Submit the request. | The system should prevent submission of an invalid date range. | To be verified during test execution. | Candidate |
| BUG_005 | Dashboard remains accessible after logout using browser Back button | Medium | High | Windows 11, Chrome | 1. Log in.<br>2. Log out.<br>3. Click the browser Back button. | The authenticated Dashboard should not be accessible after logout. | To be verified during test execution. | Candidate |

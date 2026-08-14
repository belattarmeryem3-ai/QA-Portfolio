# Leave Management Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LEAVE_001 | Verify Leave page is displayed | User is logged in | 1. Click **Leave** from the navigation menu. | N/A | Leave Management page is displayed. |
| TC_LEAVE_002 | Verify leave records are displayed | User is on the Leave page | 1. Observe the leave records. | N/A | Leave records are displayed correctly. |
| TC_LEAVE_003 | Verify user can open Apply Leave page | User is on the Leave page | 1. Open the Apply Leave option. | N/A | Apply Leave page is displayed. |
| TC_LEAVE_004 | Verify required fields validation on Apply Leave | User is on the Apply Leave page | 1. Leave required fields empty.<br>2. Click **Apply**. | N/A | Appropriate validation messages are displayed. |
| TC_LEAVE_005 | Verify leave can be submitted with valid information | User is on the Apply Leave page | 1. Select a leave type.<br>2. Select valid dates.<br>3. Enter a valid comment if required.<br>4. Submit the request. | Leave Type: Annual Leave | Leave request is submitted successfully. |
| TC_LEAVE_006 | Verify user cannot submit leave without selecting leave type | User is on the Apply Leave page | 1. Leave Leave Type empty.<br>2. Enter other required information.<br>3. Click **Apply**. | N/A | Validation message is displayed for Leave Type. |

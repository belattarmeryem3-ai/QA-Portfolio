
# Employee Management Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_EMPLOYEE_001 | Verify Employee Management page is displayed | User is logged in | 1. Click **PIM** from the navigation menu. | N/A | Employee Management page is displayed. |
| TC_EMPLOYEE_002 | Verify employee list is displayed | User is on the Employee Management page | 1. Observe the employee list. | N/A | Employee records are displayed in the list. |
| TC_EMPLOYEE_003 | Verify employee search by employee name | User is on the Employee Management page | 1. Enter an existing employee name.<br>2. Click **Search**. | Employee Name: Linda Anderson | Matching employee records are displayed. |
| TC_EMPLOYEE_004 | Verify search with non-existing employee | User is on the Employee Management page | 1. Enter a non-existing employee name.<br>2. Click **Search**. | Employee Name: XYZ_Test_999 | No matching employee record is displayed. |
| TC_EMPLOYEE_005 | Verify Add Employee page can be opened | User is on the Employee Management page | 1. Click **Add**. | N/A | Add Employee page is displayed. |
| TC_EMPLOYEE_006 | Verify employee can be added with valid data | User is on the Add Employee page | 1. Enter first name.<br>2. Enter last name.<br>3. Enter employee ID if required.<br>4. Click **Save**. | First Name: John<br>Last Name: Tester | Employee is successfully added and employee details are displayed. |
| TC_EMPLOYEE_007 | Verify required fields validation when adding employee | User is on the Add Employee page | 1. Leave required fields empty.<br>2. Click **Save**. | N/A | Appropriate validation messages are displayed for required fields. |
| TC_EMPLOYEE_008 | Verify employee details can be edited | An employee exists | 1. Open an employee record.<br>2. Edit an employee field.<br>3. Click **Save**. | First Name: UpdatedName | Employee information is updated successfully. |
| TC_EMPLOYEE_009 | Verify employee list can be reset after search | User has performed an employee search | 1. Enter search criteria.<br>2. Click **Search**.<br>3. Click **Reset**. | N/A | Search fields are cleared and the employee list is restored. |
| TC_EMPLOYEE_010 | Verify employee record can be opened from the employee list | User is on the Employee Management page | 1. Click an employee record. | Existing employee | Employee details page is displayed. |

Log in as Admin 

Log in to the application using an admin account to verify the functionalities of creating, viewing, and deleting employees via the administrative panel at http://localhost/_hr_soft/admin/View_user.php.
Log in as a Lower-Privileged User:![1](https://github.com/user-attachments/assets/f3efbfa1-70ab-4e26-bea5-649a8aebc825)
![2](https://github.com/user-attachments/assets/7c9906f7-2753-4d4b-b875-1d3f3323b9fc)


Log out of the admin account and log in as a lower-privileged user (e.g., a standard employee user).![3](https://github.com/user-attachments/assets/9e8dd787-a83f-4220-966d-62950277207d)

Confirm that this user does not have access to the administrative functionalities in the application's user interface.![2](https://github.com/user-attachments/assets/4546003e-cd56-4e3e-bbe0-905ea870f858)

Manipulate the URL:

Append the admin panel path (/admin/View_user.php) to the base URL (http://localhost/_hr_soft/).
Example: http://localhost/_hr_soft/admin/View_user.php.
Verify Access:
![4](https://github.com/user-attachments/assets/eac3b6e1-4cf0-45b0-80bf-563e8ddeaec8)

Navigate to the manipulated URL while logged in as the lower-privileged user.
Observe that the restricted admin functionalities, such as creating, viewing, and deleting employees, are accessible without proper authorization.
Test Functionality Misuse:![5](https://github.com/user-attachments/assets/b0a6b1c1-b13c-444f-be70-4b5c6fa9a1f6)

![6](https://github.com/user-attachments/assets/8100d657-4634-462c-b5cc-638dcd11cdad)
![7](https://github.com/user-attachments/assets/889dc144-3bb0-416a-8648-d4416bfc964f)

Perform actions such as deleting or creating employee records to confirm that the lower-privileged user can execute admin-level operations.
Document the Impact:

Note that this behavior violates the principle of least privilege and allows unauthorized actions, which can lead to data integrity and security issues.

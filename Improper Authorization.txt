Log in as Admin 

Log in to the application using an admin account to verify the functionalities of creating, viewing, and deleting employees via the administrative panel at http://localhost/_hr_soft/admin/View_user.php.
Log in as a Lower-Privileged User:

Log out of the admin account and log in as a lower-privileged user (e.g., a standard employee user).
Confirm that this user does not have access to the administrative functionalities in the application's user interface.
Manipulate the URL:

Append the admin panel path (/admin/View_user.php) to the base URL (http://localhost/_hr_soft/).
Example: http://localhost/_hr_soft/admin/View_user.php.
Verify Access:

Navigate to the manipulated URL while logged in as the lower-privileged user.
Observe that the restricted admin functionalities, such as creating, viewing, and deleting employees, are accessible without proper authorization.
Test Functionality Misuse:

Perform actions such as deleting or creating employee records to confirm that the lower-privileged user can execute admin-level operations.
Document the Impact:

Note that this behavior violates the principle of least privilege and allows unauthorized actions, which can lead to data integrity and security issues.

# Task 001 – Password Reset Request (Simulated Ticket)

**Issue:**  
User "jwalker" reports they cannot log into their Windows 10 workstation. The error states "The password is incorrect."

**Resolution Steps:**
1. Logged into DC1 and opened Active Directory Users and Computers (ADUC)
2. Located user `jwalker` in the `Users` OU
3. Right-clicked → Reset Password
4. Set temporary password and checked "User must change password at next logon"
5. Informed user of reset via email (simulated)

**Result:**  
User was able to log in after password reset.

---


**Screenshot:**  
![password-reset](../screenshots/001-password-reset.png)

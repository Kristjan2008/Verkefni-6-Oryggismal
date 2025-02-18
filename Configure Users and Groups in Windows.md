## Part 1: Create New Users
### Step 1: Access Local Users and Groups Manager.
* #### Question: What are the names of the accounts listed?
* ##### Answer here: Kristjan, krist, halli, User1 and Guest
* #### Question: Which group does your account belong to?
* ##### Answer here: Administrators and Users
### Step 2: Create new users.
* #### Question: What is Student01 required to do when logging in the first time?
* ##### Answer here: He has to choose a password
* #### Question: What group does Student01 belong to?
* ##### Answer here: Users
* #### Questions: From the description, can the members of the Users group make system wide changes? What can the Users group do on the computer?
* ##### Answer here: Users are prevented from making accidental or intentional system-wide changes and can run most applications
* #### Questions: Who are the group members?
* ##### Answer here: Kristjan, krist, halli, User1, Student01, Student02, Staff01 and Staff 02
### Step 3: Verify user and group permissions.
* #### Question: Were you successful in creating the new account? Explain.
* ##### Answer here: No its showed an error that said access denied
* #### Question: Were you able to navigate to www.cisco.com? Explain.
* ##### Answer here Yes it worked
## Part 2: Create New Groups
* #### Question: With the group ITEStaff highlighted, what can the members do in this folder?
* ##### Answer here: Members of ITEStaff can perform actions like reading, writing, or modifying files based on assigned permissions.
* #### Question: Which additional checkbox would you select?
* ##### Answer here: Select the "Full Control" checkbox to grant members of ITEStudent complete access to the folder.
## Part 3: Modify User and Group Permissions
### Step 1: Verify and modify folder permissions.
* #### Question: Were you successful? Explain.
* ##### Answer here: Yes. Student02 can create a folder and text document in the C:\Students folder because full control was granted to the ITEStudent group.
* #### Question: Were you successful? Explain.
* ##### Answer here: No. Student02 cannot create a folder in the C:\Staff folder because permissions for the ITEStudent group were explicitly denied.
* #### Question: Can you place a text file in the Staff folder? Can you modify the text file in folder Student02? Explain.
* ##### Answer here: No, you cannot place a file in the Staff folder because permissions for ITEStudent are denied. Yes, you can modify the text file in Student02 because the group permissions allow modifications.
* #### Question: Were you able to access the content in the folders Staff, Students\Student01 and Students\Student02? Explain.
* ##### Answer here: Yes, Staff01 can access the content in the Staff folder and modify content in Student01 and Student02 folders because of the permissions granted to the ITEStaff group.
### Step 2: Disable a user account.
* #### Question: Can you log on as Staff02? Explain.
* ##### Answer here: No, you cannot log on as Staff02 because the account is disabled. Disabled accounts cannot be used to log into the system.
### Reflection Questions
1. How would you give administrative privileges on the local computer to all the members of ITEStaff?
##### Answer here: Add the ITEStaff group to the "Administrators" group using Local Users and Groups Manager.
2. How would you deny access to a file for everyone except the owner?
##### Answer here: Navigate to the file properties > Security tab > Advanced > Disable inheritance. Remove all users/groups except the owner and explicitly assign full control to the owner.

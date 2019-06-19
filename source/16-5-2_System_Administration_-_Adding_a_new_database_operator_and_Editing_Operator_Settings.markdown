# 16.5.2 System Administration - Adding a New Database Operator and Editing Operator Settings


> System Administrators can add new database operators to their system in the Database Operators' table. They can also go back to edit their permission level and other details

**Please note: When you add a new database operator to the system, it will automatically create a new staff profile for them. If they already have a profile on the system it will be necessary to merge the two (see [16.8.1 Merging Profiles](/help/index/p/16.8.1)). When you do this, make sure that the profile you keep is the new database operator one.**

### To Add New Operator

- Click 'admin -> system administration -> Manage database operators.
- The table on this page (see below) shows you all of the operators currently in the system. Depending on the number that you have, the table may go onto subsequent pages. From here you can edit their operator settings, change their restrictions, lock, unlock or remove them, and add operators.

![Database Operators Table](16.5.2a.png)

- Right click in the table or on the menu button to the left of the row. Alternatively you can use the 'click here' button below the table.
- From the pop-up menu select 'Add new'. 
- A popup window will open requesting the new operator's basic details:

![new database operator](150a.png)

- Complete the form:
   - The email address will be the operator's log-in.
   - Choose the operator role (see [16.5.1 System Administration - Operator Permission Levels](/help/index/p/16.5.1).
   - You can choose to copy personal settings from another database operator. Many of the things you take for granted about how your system looks and works are determined by these, including headers on profiles, a particular layout for tables in your system and the tabs that you see on your home page. If in doubt, copy settings from yourself. (See [16.4.0 Personal Settings: Customising {{Lamplight}}]9/help/index/p/16.4.0)).
   - If you have multiple {{project}}s, tick the ones the operator will have access to. This does not share the operator's profile with these projects - that will need to be done separately - but it means that they will be able to view and edit information in them (depending on the access level). 
   - If you have log-in policies you can choose one here (see [16.5.5 Login Security Policies](/help/index/p/16.5.5)).
   - When you have finished, save.
   - When you add a new database operator {{Lamplight}} automatically creates a new staff profile and sends an email to their registered email account with their initial password.

### Password Issues

If the new password does not arrive it is most likely to be an issue with the recipient's email spam filter. Most inboxes have a spam folder you can check. If you are using a dummy email address however, or are not able to locate it, you can reset the password.  

- In the database operators' table (see above), click on the menu to the left the new operator (you can also bring this menu up by right clicking on the relevant row in the table). 
- Choose 'Reset password'. This will email a new password as well as displays it in a pop-up box. 
- You can write down the new password or take a screenshot and share it as appropriate.

### Editing Existing Operators

- You can go back the the Database Operators' table at any time, open the menu next to the relevant operator and choose 'Edit'.  
- This will open the original pop-up box that you saw when first adding the operator. You can change any details that you need here (see above in 'To Add a New Operator' for details). 
- Click 'save' when finished. 


###### core module


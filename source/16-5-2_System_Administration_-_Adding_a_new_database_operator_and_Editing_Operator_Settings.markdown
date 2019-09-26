# 16.5.2  <i class="fas fa-address-card"></i> System Administration - Adding a New Database Operator and Editing Operator Settings

> System Administrators can add new database operators to their system in the dtabase operators' table. They can also go back to edit their permission level and other details



**Please note: When you add a new database operator to the system, it will automatically create a new staff profile for them. If they already have a profile on the system it will be necessary to merge the two (see [16.8.1 Merging Profiles](/help/index/p/16.8.1)). When you do this, make sure that the profile you keep is the new database operator one.**  

### To Add a New Operator

- Go to 'admin -> system administration -> Database Operators And Security -> Manage database operators.

The table on this page (see below) shows you all the operators currently in the system. Depending on how many you have, the table may go onto subsequent pages. From here you can add new operators, edit settings, change restrictions, lock, unlock or remove them.

![Database Operators Table](16.5.2a.png)

- Right click in the table or on any menu button in the left-hand column. Alternatively you can use the 'click here' button below the table.
- From the pop-up menu select 'Add new'. 
- A popup window will open requesting the new operator's details:

![new database operator](150a.png)

Complete the form:
   - The email address will be the operator's log-in.
   - Choose the operator role (see [16.5.1 System Administration - Operator Permission Levels](/help/index/p/16.5.1).
   - You can choose to copy personal settings from another database operator if you want to. Many of the things you take for granted about how your system looks and works are determined by these, including headers on profiles, a particular layout for tables in your system and the tabs that you see on your home page. If in doubt, copy settings from yourself. (See [16.4.0 Personal Settings: Customising {{Lamplight}}](/help/index/p/16.4.0)).
   - If you have multiple {{project}}s, tick the ones the operator will have access to. This does not share the operator's profile with these projects - that will need to be done separately - but it means that they will be able to view and edit information in them (depending on the access level). 
   - If you have log-in policies you can choose one here (see [16.5.5 Login Security Policies](/help/index/p/16.5.5)).
   - When you have finished, save.
   - When you add a new database operator {{Lamplight}} automatically creates a new staff profile for them and sends an email to their registered email account with their initial password.

### Password Issues

If the new password does not arrive it is most likely to be an issue with the recipient's email spam filter. Most inboxes have a spam folder you can check. If you are using a dummy email address however, or are not able to locate it, you can reset the password.  

- In the database operators' table (see above), click on the menu to the left the new operator (you can also bring this menu up by right clicking on the relevant row in the table). 
- Choose 'Reset password'. The new password will be displayed in a pop-up box (it will also be emailed to the database operator.) 
- You can write down this password or take a screenshot and share it as appropriate.

The operator will need to change their password when they next login.

### Editing Existing Operators

- You can go back the the database operators' table at any time, open the menu next to the relevant operator and choose 'Edit'.  
- This will open the original pop-up box that you saw when first adding the operator. 
- You can change any details that you need here (see above in 'To Add a New Operator' for details). 

You can see a demonstration of this in our video below (please note that the layout of the system administation page has changed since this was recorded).

<iframe src="https://player.vimeo.com/video/279249125" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
- Click 'save' when finished. 


###### core module


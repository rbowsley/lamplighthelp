# 17.1.0 Adding a New {{Project}}

> When you add a new {{project}}, you will need to make decisions about how your new {{project}} and existing {{project}}s work together

When we say we’ve ‘added a new {{project}}’, what we’ve done is given you the ability to add a new {{project}} to your system. This is because a lot of the decisions about how your new {{project}} and existing {{project}}s work together are taken as you create it.

To add and amend {{project}}s, you’ll need to be a {{Project}} Administrator. This is a level above System Administrator and is only used when a system has multiple {{project}}s. You can’t add this level of access yourself but will need to ask Lamplight to do this for you.


### Overview

When you begin adding a {{project}} you can choose what (if anything) you wish to copy from an existing {{project}}. 

Copying profile fields or work areas, for example, will allow you to report on those same profile fields or work areas across both {{project}}s. If you simply create a blank {{project}} and add a new field, for example ‘Gender’, even though you may have a field of the same name in another {{project}}, because they were created separately they will not be linked in Lamplight (they’ll have a different field ID number), so you will have to report on them separately.

What happens when you ‘copy’ elements of an existing {{project}} to a new {{project}} is that the fields are shared with the new {{project}}. For example, if I copy all profile fields, the gender field will be shared. I can then run one report to show the gender of clients across both {{project}}s. However, as the fields are shared, if I delete the gender field in the new {{project}} it will delete it across all {{project}}s it is shared with.

The normal process to follow would be:

- When you create the {{project}}, share the type of fields (profile fields, work areas etc) that you want the {{project}}s to have in common
- Then go through and manually unshare any individual fields which are not appropriate
- Ask Lamplight to unshare any individual areas which you cannot unshare yourself


### Adding a new {{project}}

   - Go to the System Administrator page from the main menu, by choosing Admin > System Administration. From here, find the section called ‘Manage {{Project}}s’. 
   - The ‘Add, edit and remove {{project}}s’ option will take you to a table like this.
 	 
   xxxxxx Picture here xxxxxx
   
   - To add a new {{project}}, right click on any existing {{project}}s in the table, and when the menu appears click ‘Add new’. You’ll see this dialogue box.
 
**{{Project}} Name**

   - Enter the name of the new {{project}}. Although all {{project}} may be part of your organisation, choose a name which distinguishes it. 

**Create {{Project}} Profile**

   - Creating a {{project}} profile will create a new profile with that {{project}} name, to allow you to assign referrals etc to it.
   - If you want to have a blank {{project}}, and to start it entirely from scratch, simply leave the rest of the options blank and click save. You’ll have created a new {{project}}.
   
**Copying Settings**

   If you want your new {{project}} to incorporate elements of an existing {{project}} you can choose which one to copy settings and information from. 
   - Use the drop-down to select a {{project}}.
   - Choose which areas to copy across. When you choose an area (for example profile tabs and fields or work areas), it copies all the tabs and fields across.
   - Once completed, click save, and your new {{project}} will be created.
   
**Changing Sharing**

   Now you’ve set-up your {{project}}, you may wish to adjust some of your sharing settings.
   - Automatic Sharing. Some field are automatically shared across {{project}}s and cannot be unshared. These include:
      - Attendance types and roles
      - Name title and suffixes
      - Referral success and direction categories
      - Grant types
      - Wards and Boroughs

**Non-Shared Fields**

   Some information can’t be shared across projects but can be entered manually in each project. As the fields are not copied across they won’t be shared, and so can’t be reported on across projects. If you have a great deal of information to enter, you can ask Lamplight to copy it across for you (however, it still will not remain linked to the initial project). This includes case categories, for example.

**Unsharing fields**

   You can share or unshare custom fields in profiles and work records yourself from the System Administration menu.

   - Go to the ‘Manage Drop-down lists’ section. Within this, for profile fields, go to ‘Profile custom tabs and fields’. 
   - Under this select the option ‘view, add and edit tabs and fields on profiles’. 
   - When this screen opens, on the left you’ll see a list of your tabs. 

   xxxxxx picture here xxxxxx

   - Select a tab, you’ll see new information relating to it appear in the middle column.
   
   xxxxxx picture here xxxxxx
   
   - Sharing must be enabled both for the field and for the tab it is in. For example, if I share the gender field, but not the ‘personal’ tab where that field is held, I won’t be able to see either the tab or the field in profiles in the second project. 
      - To manage tab sharing, double click in the middle column, on the text ‘Tab label:’.
      - To manage field sharing select the field, then when information appears in the right-hand column, double click on ‘Field name’.
   
   xxxxxx picture here xxxxxx
   
   - Each option will open a dialogue box of options, which will include a list of projects in your system. Simply tick or untick the boxes to enable to disable sharing with that project.
   
   xxxxxx picture here xxxxxx
 
   You can use this method for any profile custom tabs and fields, as well those in other types of records which can be found in the same ‘Manage Drop-down lists’ section of the System Administration page. 
   Be sure to distinguish between custom fields in outcomes, which are extra fields in your outcomes records which you can share yourself, and the outcome measures themselves, which you can’t. Evaluations can be managed through the ‘Manage evaluations’ settings.

**Unsharing other fields**

   There are some fields you won’t be able to unshare yourself. If you ask Lamplight, we’ll be happy to help. These include:
   - work areas
   -	locations
   -	outcomes
   
**Changes and warnings for system administrators**

   Once you add multiple projects, the system administrator role becomes more limited. System administrators are now no longer able to make changes across the whole system. This includes access to global settings, and a variety of other features. These settings can now only be accessed by a project administrator.
   
   It is important for system and project administrators to come to an understanding about what changes they can make in their own projects, and how these will affect other projects. For example, while a system administrator can add a new work area in their project without it affecting others (although as a stand-alone work area it wouldn’t be possible to use it to report across projects), if they remove or change a shared work area this will remove it or change it for every project which uses it.

###### core module

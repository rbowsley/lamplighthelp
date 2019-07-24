# 17.1.0 Adding a New {{Project}}

> When you add a new {{project}}, you will need to make decisions about how your new and existing {{project}}s work together

When we say we’ve ‘added a new {{project}}’, what we’ve done is given you the ability to add a new {{project}} to your system. This is because a lot of the decisions about how your new and existing {{project}}s work together are taken as you create it.

To add and amend {{project}}s, you’ll need to be a {{Project}} Administrator. This is a level above System Administrator and is only used when a system has multiple {{project}}s. If you do not already have a {{Project}} Administrator, or your Project Admin can't add more operators of this level to the system, contact us to sort this out for you.

### Overview

When you begin adding a {{project}} you can choose what (if anything) you wish to copy from an existing {{project}}. 

Copying profile fields or {{workarea}}s, for example, will allow you to report on those same profile fields or {{workarea}}s across both {{project}}s. If you simply create a blank {{project}} and add a new field, for example ‘Gender’, even though you may have a 'Gender' field in another {{project}}, because they were created separately they will not be linked in Lamplight (they’ll have a different field ID number), so you will have to report on them separately.

When you ‘copy’ elements of an existing {{project}} these fields are shared with the new {{project}}. For example, if I copy all profile fields, the 'Gender' field will be shared. I can then run one report to show the gender of clients across both {{project}}s. However, as the fields are shared, if I delete the 'Gender' field in the new {{project}} it will delete it across all {{project}}s it is shared with.

The normal process to follow would be:

- When you create the {{project}}, share the type of fields (profile fields, {{workarea}}s etc) that you want the {{project}}s to have in common.
- Once you have finished this, go through and manually unshare any individual fields which are not appropriate.
- Ask Lamplight to unshare any individual areas which you cannot unshare yourself.


### Adding a new {{project}}

   - Go to 'admin -> system dministration -> {{Project}}s -> Manage projects’. 
   - You will see a table like this.
 	 
   ![{{Project}}s Table](17.1.0a.png)
   
   - To add a new {{project}}, right click on any existing {{project}}s in the table, and when the menu appears click ‘Add new’. 
   - You’ll see this dialogue box:
   
![Add a New {{Project}} Dialogue Box](17.1.0b.png)
 
**{{Project}} Name**

   - Enter the name of the new {{project}} which will distinguish it from any other {{project}}s on your system.  

**Create {{Project}} Profile**

   - Creating a {{project}} profile will create a new profile in the system with that {{project}} name which will allow you to assign referrals etc to it.
   - If you want to have a blank {{project}} so that you can start entirely from scratch simply leave the rest of the options blank and click save. You’ll have created a new {{project}}.
   
**Copying Settings**

   If you want your new {{project}} to incorporate elements of an existing {{project}} you can choose which one to copy settings and information from. 
   - Use the drop-down to select a {{project}}.
   - Choose which areas to copy across. When you choose an area (for example profile tabs and fields or {{workarea}}s), all of the tabs and fields or {{workarea}}s are copied across (this does not affect any of the data in the original {{project}}).
   - Once completed click save, and your new {{project}} will be created.
   
### Changing Sharing

Once you’ve set-up your new {{project}}, you may want to adjust some of the sharing settings.
   - Automatic Sharing. Some fields are automatically shared across {{project}}s and cannot be unshared. These include:
      - Attendance types and roles.
      - Name title and suffixes.
      - Referral success and direction categories.
      - Grant types.
      - Wards and boroughs.

**Non-Shared Fields**

   Some information needs to be manually entered in each {{project}}. As the fields are not copied across they won’t be shared, and can’t be reported on across {{project}}s. If you have a large amount of information to enter you can ask Lamplight to copy it across for you (however, it still will not be linked to the initial {{project}}). This includes case categories, for example.

**Unsharing Fields**

   You can share or unshare custom fields in profiles and {{activity}} records yourself from the System Administration menu.

   - Go to the ‘Manage Custom Fields and Drop-down lists’ section. 
   - Within this, if you are looking at profile fields for example, go to ‘People and Organisations -> Manage custom tabs and fields on profiles’. 
   - When this screen opens, on the left you’ll see a list of your tabs. 

   ![Custom Profile Fields in System Admin](17.1.0c.png)

   - When you click on a tab you’ll see new information relating to it appear in the middle column.
   
   ![The Fields Column](17.1.0d.png)
   
   - If you want to share a field across {{project}}s, sharing must be enabled both for the field and for the tab it is in. For example, if I share the gender field, but not the ‘personal’ tab where that field is held, I won’t be able to see either the tab or the field in profiles in the second {{project}}. 
      - To edit tab sharing, double click in the middle column, on the text ‘Tab label:’.
      - To edit field sharing select the field, then when information appears in the right-hand column, double click on ‘Field name’.
   
   [Tab and Field Links](17.1.0e.png)
   
   - Each option will open an editing box, at the bottom of which is a list of the {{project}}s in your system. Simply tick or untick the boxes to enable to disable sharing with that {{project}}. The box of the {{project}} where a field was added will always be ticked by default and greyed out. 
   
   ![List of {{Project}}s](17.1.0f.png)
 
You can use this method for any profile custom tabs and fields, as well those in other types of records which can be found in the same ‘Manage Custom Fields and Drop-down lists’ section of the System Administration page.   

Be sure to distinguish between custom fields in {{outcome}}s, which are extra fields in your {{outcome}} records which you can share yourself, and the {{outcome}} measures themselves, which you can’t.  

Evaluations can be managed through the ‘Manage evaluations’ settings.  

**Unsharing Other Fields**

   There are some fields you won’t be able to unshare yourself. If you ask Lamplight, we’ll be happy to help. These include:
   - {{workarea}}s.
   - locations.
   - {{outcome}}s.
   
### Changes and Warnings for System Administrators

   Once you add multiple {{project}}s, the System Administrator role becomes more limited. System administrators are now no longer able to make changes across the whole system. This includes access to global settings, and a variety of other features. These settings can now only be accessed by a Project Administrator.
   
   It is important for System and Project Administrators to come to an understanding about what changes they can make in their own {{project}}s, and how these will affect other {{project}}s. For example, while a System Administrator can add a new {{workarea}} in their {{project}} without it affecting others, if they remove or change a shared {{workarea}} this will remove it or change it for every {{project}} which uses it.

###### core module

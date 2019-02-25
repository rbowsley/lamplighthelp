# 16.7.3    Adding and Editing Custom Tabs and Fields to Work and Other Records

> It is possible to add additional tabs and fields to your {{work}}, {{outcome}} and other records through System Administration.

In the section 'Manage drop-down lists' you'll see options at the bottom to add custom tabs and fields for each type of record.

![System Admin - Add fields to records]({{imgpath}}1217a.png)

Each type of record works on the same principle, with the example below being for {{work}} records.  
The system is almost identical to adding Custom tabs and fields on profiles.  

**Adding fields to a work record**

Choose 'View, add and edit custom field on work records'.  You'll see three columns, with the first showing you a list of tabs available on your work records.  Depending on your set-up you may see one or more of the three standard tabs on the work record (When and where, Attendance, Details).  This is where you have custom fields added to these tabs.  You'll also see any custom tabs you have created.

Click on a tab on the left, and you'll see the fields for that tab in the centre column.  If you then click on a field, you'll see the field information, and options if applicable in the right column.  As shown below.

![System admin - Adding custom fields to records](1218a.png)

**Creating a new tab**

To create a new tab, select the button 'Click here to add' in the left-hand column.  You'll see a small pop-up box.  This will open a small pop-up box with the tab information.  In here you can name the tab, and select various options.  Some of these options are redundant in records, and apply only to profile fields.

* What type of person is this for:  You need to select at least one option here for the tab to show in profiles.
* Restrict this field to managers/admins?:  Although you can tick this field, it does not function in this record.
* Projects: You can select which projects (If you have more than one project) this field should display for.
* You may also see fields about publishing, if you have the publishing module.  See section [24.0 Publishing Module](/help/index/v/{{version}}/p/24.0)
Click 'Save' to save the tab.

**Important** You must always add a field to a tab, to ensure it remains editable and visible in System Administration.  If you do not, you'll have an empty tab in your record which you will be unable to edit.  In this case, please contact Lamplight for support.

![System Admin - tab information]({{imgpath}}1219a.png)

**Adding fields**

Select the required tab, and in the middle column, choose the button 'Click to add'. In the right-hand column, you'll see a new section appear 'Field: Click to add.'  Double click on the non-bold text 'Field: Click to add ‘and a pop--up box will open.  Again, some of the options show here are redundant for work records. (For types of custom field in {{activity}} records see XXXXXXXXX).

![System Admin - field information]({{imgpath}}1220a.png)

* Text: This is the name of the field.
* What type of person is this for:  No answer can be selected here, as records show all fields for all users.

* Type: This selects the type of field you will be creating.  By default, a new field will be a 'select' field, unless changed.  See information on types of fields below.

* Is this a required for: IF this is selected, a user will not be able to exit the tab without entering information.  Use very cautiously.
* Restrict this field to managers/admins?:  Although you can tick this field, it does not function in this record.
* Projects: You can select which projects (If you have more than one project) this field should display for.
* You may also see fields about publishing, if you have the publishing module.  See: 
Click save once you have completed the appropriate fields.

**Editing a tab**

To edit a tab, select the tab in the left-hand column, and when the tab information shows in the middle column, double click on the text 'Tab name', and edit the existing information (as above)


**Editing a field**

Choose the field you wish to edit in the centre column, and select it.  In the right-hand column, you will see the field information appear (you may need to scroll up if you have a long list of fields.)  Double click on the non-bold text, where it says 'Field: _name_.  From here follow the process as above to edit and save the field.

 
__Adding fields to a system standard tab__

All records have the tabs 'Where and Where', 'Attendance', ( this may be called 'respondent' or 'Involved' in some cases), and Details.  You can't edit of delete the fields which already exist in these tabs (this can only be done by Lamplight), but you can add additional fields to them by 'creating' them in System Admin.  Create a tab with the correct name as below, (capitalisation is essential), and add fields to it.  

![System Admin - adding fields to system tabs]({{imgpath}}1221a.png)

_{{Work}} records_
When and where
Attendance
Details

_{{Outcome}} records_
When and where
Respondent (if you have this tab)

_{{Referral}} records_
When and where
Attendance (if you have this tab)
Involving (if you have this tab)
details

_{{Grant}} records_
When and where
Attendance
details


###### core module


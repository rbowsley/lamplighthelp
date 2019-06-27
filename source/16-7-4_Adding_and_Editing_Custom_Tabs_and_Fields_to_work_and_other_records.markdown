# 16.7.4    Adding and Editing Custom Tabs and Fields to Work and Other Records

> It is possible to add additional tabs and fields to your {{work}}, {{outcome}} and other {{activity}} records through System Administration

In the section 'Manage Custom Fields and Drop-down Lists' you'll see options for each type of record to manage custom tabs and fields.

![System Admin - Add fields to records]({{imgpath}}1217a.png)

Each type of record works on the same principle, with the example below being for {{work}} records.  
The process is almost identical to adding custom tabs and fields on profiles.  


**Adding Fields to a {{Work}} Record**

- Go to '{{Work}} Records Custom Tabs and Fields -> Manage custom tabs and fields in work records'.
- You'll see three columns, with the first showing you a list of tabs available on your work records.  
- Depending on your set-up you may see one or more of the three standard tabs on the work record (When and where, Attendance, Details).  This is where you have custom fields added to these tabs. You will not see the standard fields in these tabs.
- Click on any tab on the left and you'll see the fields for that tab in the centre column.  
- If you then click on a field, you'll see the field information, and options if applicable in the right column, as shown below.

![System admin - Adding custom fields to records](16.7.4a.png)


**Creating a New Tab**

- Select 'Click here to add' at the bottom of the left-hand column.  
- Fill in the details of the pop-up box:
   - Text: This will appear as the tab name
   - What type of person is this for?: You can't edit this field - it is only applicable to custom tabs in profiles.
   - Restrict this field to managers/admins?:  Although you can tick this field, it does not function in this record.
   - Projects: You can select which projects this tab will apply to (if you have more than one {{Lamplight}} project).
   - You may also see fields about publishing, if you have the Publishing Module.  See section [28.0.0 Publishing Module](/help/index/v/{{version}}/p/28.0.0)
   
![System Admin - Tab Information](1219a.png)

   - Click 'Save' to save the tab.

**Important: You must always add a field to a tab, to ensure it remains editable and visible in System Administration.  If you do not, you'll have an empty tab in your record which you will be unable to edit.**


**Adding Fields (the Middle Column)**

When you click on a tab in the left-hand column, the middle column will show you a list of the fields in that tab.
      
- To add a new field to a tab, click the 'click to add' button at the bottom of the column in the middle box. 

![Add a Field to a Tab](16.7.2e.png)

- The box on the right-hand side of the screen will then open.
- In the right column, double click over the text 'Field name: click to add'.

![Adding a new field](16.7.2f.png)

- A pop-up box will open. Complete the details with:
   - The title of the field: this is the text you will see next to the field in the new tab.
   - Which type of profiles it will be applicable to: no answer can be selected here, as records show all fields for all users.
   - The type of field required: for more on types of field see [16.7.3 Custom {{Work}} and Other Record Tabs and Fields](/help/index/p/16.7.3).
   - Whether it is a required field: if you choose this option it will not be possible to edit the tab and save it without putting data in this field.
   - Whether to restrict the field to Managers and Admins: although you can tick this field, it does not function in this record.
   - If you have more than one project, you have the option to share this new field across your projects.
   - If you have the Publishing Module, you can also specify whether data in this field should be published. See [28.1.0  Publishing Module Security](/help/index/p/28.1.0) for more information about the Publishing Module and the controls in place.
   - Click to save. The third panel will update showing the information added. 
     

**Setting Options**
   
- In the right column, you’ll now see the options for your field.  (If not, click on the field name - the grey button in the middle column.)
- This text in the right column will show you the name, and type of field, and if access to it is restricted.  If it’s a field that requires no options, such as ‘Date of Birth’ then that’s all you’ll see.  
- If you can enter options you’ll see a ‘click to add’ button, and a text box.
- The easiest way to enter your options is using the text box at the bottom of the column. Type or paste your options in here, separated by semi-colons (no spaces), then click the 'Add' button below the box to save. 

![Adding Options to a Field](16.7.2h.png)

- It is also possible to add them one at a time by using  the ‘click to add’ button. 
- You'll see your options appear in the list under 'Options'. 

![Final Option Text in Field](16.7.2i.png)

Repeat this process until you have added all the tabs, fields and options that you require.


**Editing a Tab**

To edit a tab, select it in the left-hand column, and when the information shows in the middle column, double click on the text 'Tab name', and edit the existing information (as above).


**Editing a Field**

Choose the field you wish to edit in the centre column, and click on it.  In the right-hand column, you will see the field information appear (you may need to scroll up if you have a long list of fields.)  Double click on the non-bold text, where it says 'Field: _name_.'  From here follow the process as above to edit and save the field.

 
**Adding Fields to a Standard System Tab**

All records have the tabs 'Where and Where', 'Attendance', ( this may be called 'Respondent' or 'Involved' in some cases), and Details.  You can't edit of delete the fields which already exist in these tabs (this can only be done by Lamplight), but you can add additional fields to them by 'creating' them in System Admin.  Create a tab with the correct name as below, (capitalisation is essential), and add fields to it.  

![System Admin - adding fields to system tabs]({{imgpath}}1221a.png)

- {{Work}} records
When and where
Attendance
Details

- {{Outcome}} records
When and where
Respondent (if you have this tab)

- {{Referral}} records
When and where
Attendance (if you have this tab)
Involving (if you have this tab)
details

- {{Grant}} records
When and where
Attendance
details


###### core module


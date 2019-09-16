# 16.7.5 Adding Custom Columns to the Attendance Table

> You can add custom columns to the attendance table you see in {{work}} records



The other option you'll see in '{{Work}} Record Custom Tabs and Fields' is 'Manage custom columns on the attendance table'.  

If you look at the 'Attendance' tab in a {{Work}} record you will see the attendance table. There are a number of columns, including name, attendance type, and role.  It's possible to add additional custom columns here (you may already have some.) However, the attendance table can become quickly crowded if you add too many columns, and so consider what you need carefully.

### Adding a New Column
- Go to 'admin -> system adminitsration -> Manage Custom Fields and Drop-down Lists -> {{Work}} Records Custom Tabs and Fields -> Manage custom columns on the attendance table'.
- You will see any existing custom columns in the left-hand column, under 'Current Sets'.
- To add a new one, click the 'click to add' button' at the bottom of this column. This will bring up a new 'set' in the middle column.
- Click on the text 'click to add' (this will be on the second line down, not the title). 
- This opens up a pop-up box with the following fields:
   - Text: the name of the column. Keep it short, as it will appear in the header row of the table.
   - What type of person is this for?: there are no options in this field, as the column will appear for all types of person.
   - Restrict this field to managers/admins?: although you can tick this field, it does not function in this record.
   - {{Project}}s: if you have more than one {{project}} in your system, you can select ones the field will be displayed in. 
   - If you have the Publishing Module you will also see fields about publishing. See [28.3.0 Publishing Module: Publishing Records to the Remote Site](/help/index/p/28.3.0). 
   - Click 'Save' to save the tab.

**Important** You must always add a field to a column as soon as you create it to ensure it remains editable and visible in System Administration. If you do not, you'll have an empty column in your record which you will be unable to edit. In this case, please contact Lamplight for support.

### Adding a Field
- In the middle column, choose the button 'Click to add'. 
- A new section will now appear in the right-hand column: 'Column: Click to add.' 
- Double click on the non-bold text (not the title) 'Column name:Click to add'
- A pop-up box will open. 

![Custom Column Fields](16.7.5a.png)

- Some of the options shown here will not be relevant to the attendance table. 
- Text: This is the name of the field.
- What type of person is this for: No answer can be selected here, as records show all fields for all users.
- Type: This selects the type of field you will be creating. By default, a new field will be a 'select' field, unless changed. (For types of custom field see [16.7.3 Types of Custom Tab and Field in {{Activity}} Records](/help/index/p/16.7.3). 
   - Reporting is more limited on custom attendance table fields than for normal fields in a {{work}} record.  You can use them to present your {{report}} (as either row or column data) in {{work} {{report}}s, and display them in a person's {{work}} records profile tab, but they can't be used in {{group}}s, and only in data views using a custom template. 
   - Captions and fixed text fields do not work with attendance table columns (even though it is still possible to select them.) If you create these then the attendance table will not display correctly.
   - Look-up fields will function only as text boxes.
   - Radio fields will not show any options.
- Is this a required field?: If this is selected, a user will not be able to exit the tab without entering information. Use very cautiously.
- Restrict this field to managers/admins?: Although you can tick this field, the column will still be visible to all operators.
- Projects: You can select which projects this field should display in (if you have more than one {{Lamplight}} project).
- If you have the Publishing Module you will also see fields about publishing. For more on this see [28.0.0. Publishing Module](/help/index/p/28.0.0). 
- Click 'save' once you have completed the appropriate fields.

### Editing a Column
- Select the set in the left-hand column.
- Double click on the text 'Set label' in the middle column.
- Edit the existing information (as above).

### Editing a Field
- Click on the field you wish to edit in the centre column. 
- In the right-hand column, you will see the field information appear (you may need to scroll up if you have a long list of options.) 
- Double click on the non-bold text 'Column name:'. From here follow the process as above to edit and save the field.


##### Tags
System admin
Activity

###### core module

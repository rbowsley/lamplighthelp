# 16.7.2   Adding and Editing Profile Custom Tabs and Fields

> Profile information for {{people}} and {{org}}s is captured with custom tabs and fields

{{Lamplight}} enables you to set up and customise the tabs and fields that appear on profiles. You can have as many of these as you need to capture different information. Different types of profile will have their own custom tabs. 

**To Add Custom Tabs and Fields**

- Go to admin on the menu bar and click 'system administration'.
- Under the 'tabs and fields' section, click on 'view, add and edit tabs and fields on profiles'.

If you are doing this for the first time, you will see a fairly blank screen:

![Setting up custom fields and tabs]({{imgpath}}146a.png)

The left-hand panel lists the tabs currently set up. The central panel will list the fields available in a particular tab. The right-hand panel will show details for a particular field within a tab.

If you have already set some tabs and fields up, there will be more buttons displayed in the left- hand column. Each button represents a tab.

- In the first box on the left-hand side, click on the button marked click to add.

PICTURE HERE

- In the middle box, double click over the text 'Tab label: click to add'.

![Setting the tab name](146c.png)

- Complete the pop-up box:
   - Text - this will be the title of the field that appears in the profile
   - Type of {{person}} - you must choose what type or types of {{person}} this new field is for. If you do not choose anything here then the new tab will not be visible on any profiles.
   - Roles - you can also choose to limit this tab to {{people}} or {{org}}s with particular roles.
   - Projects - if you have more than one project in your system, you can choose to share this tab so that it is also visible in other projects. When tabs and fields are shared, it is possible to report information across projects.
- Once you have finished, click the 'save' button in the bottom right corner. 
- You will now see the details you’ve added in the middle box.


**It is important that fields are added immediately after creating a new custom tab, otherwise the tab will not be saved correctly, and you will not be able to see it to delete it.**



- To add fields to the tab, click the 'click to add' button at the bottom of the column in the middle box. The box on the right-hand side of the screen will then open.
- In this third box, double click over the text 'Field name: click to add'.

![Adding a new field]({{imgpath}}146d.png)

- Complete the pop-up box with:
   - The title of the field (this is the text you will see in the profile when you have saved the tab)
   - Which type of profiles it will be applicable to (both the type of {{person}} and the role. It is important that you fill these in, or the field will not be visible in any profiles
   - The type of field required. For more on types of field see XXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   - Whether it is a required field (if you choose this option it will not be possible to edit the tab and save is without putting data in this field).
   - Whether to restrict the field to managers and admins. IF you select this it means that  means that database operators with lower levels of access will not see these fields or be able to add data to them.
   - If you have more than one project, you have the option to share this new field across your projects.
   - If you have the publishing module enabled, you can also specify whether data in this field should be published - although the profile needs to be published as well before any data becomes available. See [24.1.0  Publishing module security](/help/index/p/24.1.0) for more information about the publishing module and the controls in place.
- Click to save. The third panel will update showing the information added. 
- If a select box or multi-select box has been chosen you can now add options within the field. This can either be done by adding one option at a time using the ‘click to add’ button, or by adding several at a time in the text box at the bottom. If using the text box, each item should be separated by a semi-colon without a space. 

![Adding the option text](146f.png)

Repeat this process until you have added all the tabs, fields and options that you require.

**Adding linked fields**

You may want to link fields together so that you can enter multiple records under a single field (for more on this see XXXXXXXXX)
![Adding linked fields](146g.png). Remember, if you do this you will not be able to use the data in the linked fields for reporting, creating {{group}}s or {{group data views}}. This is most suitable for historic information you need to hold but do not need to report on, such as previous addresses.

- Create the fields you wish to link on the same tab, and make sure that they are next to one another in the correct order. 
- Select them both. To do this, click and hold the left mouse button to the left of the first field you want to link. A small red rectangle will appear. 
- Still holding the left mouse button down, move the mouse so that the red rectangle covers all the fields you wish to link together. The backgrounds of the fields being linked will change colour. 

![Adding linked fields part 2](146h.png)

- When you have selected all the fields you want to link together, release the left mouse button. When you do this the links will be saved, and the background colours change to show this.
- You can create several groups of linked fields on the same tab. These links are indicated by the different background colours of the fields.

**Changing the order of fields in a tab**

You can re-order tabs, fields and options by dragging them to the required position. Hold the mouse cursor over the button representing the tab/field/option you want to move, click and hold the left mouse button, and move the tab/field/option up or down the list until it's in the right place. Let go of the mouse button and the tab/field/option will drop into position and the new order will be saved.

**Editing tabs and fields**

You can return to this screen at any time to edit or add tabs and fields. 

It is best to only edit fields or options to correct typing mistakes or make clarifications. You should not edit fields or options if you change the meaning of that field/option text. 

If you edit a field, be aware that when you change the title of a field this will not change the data that is already stored there. For example, if you changed the options in a 'gender' field, editing 'male' to 'female' and vice-versa, all your service users whose genders had previously been recorded as 'male' would now show as 'female', and vice versa. 


###### core module


# 16.7.2   Adding and Editing Profile Custom Tabs and Fields

> Profile information for {{people}} and {{org}}s is captured with custom tabs and fields

{{Lamplight}} enables you to set up and customise the tabs and fields that appear on profiles. You can have as many of these as you need to capture different information. Different types of profile will have their own custom tabs. 

### To Add Custom Tabs and Fields

- Go to admin on the menu bar and click 'system administration'.
- Under the 'tabs and fields' section, click on 'view, add and edit tabs and fields on profiles'.

If you are doing this for the first time, you will see a fairly blank screen:

![Setting up custom fields and tabs]({{imgpath}}146a.png)

   - The left-hand panel lists the tabs currently set up. (There are some default tabs in profiles, Contact detailsfor example, whic you can't edit. You will not see them in this list).
   - The central panel will list the fields available in a particular tab. 
   - The right-hand panel will show details for a particular field within a tab.


PICTURE HERE

   - **To Add a New Tab**
   
   - In the first box on the left-hand side, click on the button marked click to add.

   xxxxxx   PICTURE HERE xxxxxx
   
   - In the middle box, double click over the text 'Tab label: click to add'.

   ![Setting the tab name](146c.png)

   - Complete the pop-up box:
      - Text - this will be the title of the field that appears in the profile
      - Type of {{person}} - you must choose what type or types of {{person}} this new field is for. If you do not choose anything here then the new tab will not be visible on any profiles.
      - Roles - you can also choose to limit this tab to {{people}} or {{org}}s with particular roles.
      - Projects - if you have more than one project in your system, you can choose to share this tab so that it is also visible in other projects. When tabs and fields are shared, it is possible to report information across projects.
   - Once you have finished, click the 'save' button in the bottom right corner. 
   - You will now see the details you’ve added in the middle box.

**Whenever you create a new tab it is essential to add at least one field immediately, even if you later remove it. If you do not do this the tab will save correctly, so it will show in the profile, but you will not be able to edit or delete it in system admin.**


   - **Adding Fields (the Middle Column)**
   
   - When you click on a tab in the left-hand column, the middle column will show you a list of the fields in that tab.
   
   xxxxxx Picture here xxxxxx
   
   - To add a new field to a tab, click the 'click to add' button at the bottom of the column in the middle box. 
   - The box on the right-hand side of the screen will then open.
   - In the right column, double click over the text 'Field name: click to add'.

![Adding a new field]({{imgpath}}146d.png)

   - A pop-up box will open. Complete the details with:
      - The title of the field (this is the text you will see in the profile when you have saved the tab)
      - Which type of profiles it will be applicable to (both the type of {{person}} and the role. It is important that you fill these in, or the field will not be visible in any profiles
      - The type of field required. For more on types of field see XXXXXXXXXXXXXXXXXXXXXXXXXXXXX
      - Whether it is a required field (if you choose this option it will not be possible to edit the tab and save it without putting data in this field).
      - Whether to restrict the field to managers and admins. If you select this it means that  means that database operators with lower levels of access will not see these fields or be able to add data to them.
      - If you have more than one project, you have the option to share this new field across your projects.
      - If you have the publishing module enabled, you can also specify whether data in this field should be published - although the profile needs to be published as well before any data becomes available. See [24.1.0  Publishing module security](/help/index/p/24.1.0) for more information about the publishing module and the controls in place.
   - Click to save. The third panel will update showing the information added. 
   
   
   **Setting Options**
   
   - In the right column, you’ll now see the options for your field.  (If not, click on the field name. (The grey button in the middle column.)
   - This text in the right column will show you the name, and type of field, and if access to it is restricted.  If it’s a field that requires no options, such as ‘Date of Birth’ then that’s all you’ll see.  
   - If you can enter options you’ll see a ‘click to add’ button, and a text box.
   
   xxxxxx Picture here xxxxxx
   
   - The easiest way to enter your options is using the text box at the bottom of the column. Type or paste your options in here, separated by semi-colons (no spaces). For example, Male;Female;Other, then click the 'Add' button below the box to save. 
   - It is also possible to add them one at a time by using  the ‘click to add’ button. 
   - You'll see your options appear in the list under 'Options'. 

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
- If you wish to remove a link from fields in a tab, click the left mouse button and drag the red rectangle back over the group of linked fields. This will remove the link.

**Changing the order of fields in a tab**

You can re-order tabs, fields and options by dragging them to the required position. 

- Hold the mouse cursor over the button representing the tab/field/option you want to move, click and hold the left mouse button
- Drag the tab/field/option up or down the list until it's in the right place. 
- Let go of the mouse button and the tab/field/option will drop into position and the new order will be saved.

**Editing tabs and fields**

You can return to this screen at any time to edit or add tabs and fields. 

It is best to only edit fields or options to correct typing mistakes or make clarifications. You should not edit fields or options if you change the meaning of that field/option text. 

If you edit a field, be aware that when you change the title of a field this will not change the data that is already stored there. For example, if you changed the options in a 'gender' field, editing 'male' to 'female' and vice-versa, all your service users whose genders had previously been recorded as 'male' would now show as 'female', and vice versa. 

To edit the tab or field:

 - Double click on the text: ‘Field name’, or ‘Tab label’.  
 - Make the changes you want, and press 'enter' on your keyboard to save.You can now edit the options.
 
 To edit a field option:
 
 - Double click on the text of the optio, , e.g. 'Female'. This will open up the dialogue box.
 - Make the changes that you need, then press 'enter' on your keyboard to save. 
 
 **Deleting Tabs, Fields and Options**
 
 To delete any tab, field or option:
 
 - Click the 'Del' button to the right of whichever you want to delete. 


###### core module


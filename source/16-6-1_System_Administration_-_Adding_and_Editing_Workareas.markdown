# 16.6.1 System Administration: Adding and Editing {{Workarea}}s and {{Subworkarea}}s

> In system administration there is a list of the {{workarea}}s you have in your system. You can add to and edit these. 

{{Workarea}}s and {{subworkarea}}s are managed in a similar way to other lists in system administration (see section [16.6.0  System Administration - Lists](/help/index/p/16.6.0)).

### Things to Consider When Making Changes to {{Workarea}}s

- When a work record is saved, the {{workarea}} and {{subworkarea}}s selected within that record are saved with it.  
- If you edit the {{workarea}} or {{subworkarea}} in system administration this will change the {{workarea}} or {{subworkarea}} in all the records where the  original one was recorded. For example, if you edit Counselling so that it is now Sports, every record that had a {{workarea}} of Counselling will now have one of Sports.  
- If you edit the name, you will no longer be able to filter or report on the previous {{workarea}}. As in the above example, the list of filters for {{report}}s or {{group}}s will show Sports, not Counselling. 
- If you delete a {{workarea}} or {{subworkarea}} you will not be able to filter by it for {{report}}s, {{group}}s or when viewing {{activity}} records. However, if you run a report showing all {{work}} then choose to present it by {{workarea}} or {{subworkarea}}, the deleted ones will still be shown in the table (providing there is data recorded to show). (For more on reporting, see [13.0.0 Reporting](/help/index/p/13.0.0), and for {{group}}s see [11.0.0 {{Group}}s](/help/index/p/11.0.0).)
- For this reason we suggest not removing work areas until then end of your reporting period.
- When you delete a {{workarea}} you are only deleting the category, not any of the historic work records related to it.

### Adding a New {{Workarea}}

{{Workarea}}s are added and edited in the same way as other drop-down lists, but they have another subset ({{subworkarea}}s) to think about. 

![Editing {{Workarea}}s and {{Outcome}}s](145a.png)

- Go to 'system admin -> Manage Custom Fields and Drop-down Lists -> {{Activity}} Records -> {{Workarea}}s.
- Existing {{workarea}}s are shown at the top. Scroll down the screen to find the box at the end with the text 'double-click to add'. 
- Double click on this box, and it will become a text box which you can edit. Enter the name of your new {{workarea}} here, then press 'enter' on your keyboard to save. **Do not click outside this box until you have saved as this may cause the system to hang**. If this does happen you will need to leave the page and open it again. 
- Once you have saved the {{workarea}}, you can create the first {{subworkarea}} for it in the 'double-click to add' box below. You do this in the same way as for the initial {{workarea}} textbox, so remember to press 'enter' to save each time. 
- Repeat this process to add any {{subworkarea}}s you need. 
- If the {{workarea}} already exists and you simply want to create a new {{subworkarea}}, find the {{workarea}} in the list. Under the  existing {{subworkarea}}s there is a 'double-click to add' box. The process for adding is the same as described above.

![Adding a {{Subworkarea}}](16.6.1a.png)

- Always create and save your {{workarea}} so that it appears in bold before adding the {{subworkarea}}s below it. 
- We would recommend that colours are added to {{workarea}}s after the headings have been entered. To do this,  double-click over 'Background colour' and move the cursor around the colour pad. When you have the colour you would like, press 'save change'.

[Adding Colour to a {{Workarea}}](16.6.1b.png)
 
**Editing {{Workarea}}s**

Before editing or deleting {{workarea}}s please see the notes above. As a general rule, you should only change the name of the {{workarea}} if the meaning is staying the same, for example due to a spelling error or a re-brand. 

- Find the text that you need to edit and double-click on it.  
- Make the changes then press enter on your keyboard to save.

**Deleting a {{Workarea}} or {{Subworkarea}}**

Before you delete a {{workarea}} or {{subworkarea}} see 'Things to Consider' above. 

You can delete a whole {{workarea}} with all its related {{subworkarea}}s in one go, or choose single {{subworkarea}}s.

- Find the {{workarea}} or {{subworkarea}} in the list. 
- Left click on it and hold the mouse key down, then drag the box containing the {{workarea}} or {{subworkarea}} to the grey 'Drag here to delete' box at the end of the page. 
- Drop it in the box. (If you have just created the {{workarea}} you will need to leave this page and return before you can delete it).
- This is now deleted. You do not need to do anything else, but it will continue to show in the grey box until you leave this page and re-open it. 

[Deleted {{Workarea}}](16.6.1c)


###### core module


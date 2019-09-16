# 21.1.1  {{Comm}} Module: Adding, Editing and Deleting {{Comm}} Templates

> {{Comm}} templates enable you to save frequently-used letters or emails so that you can use them to create new communications quickly and easily



{{Comm}} templates can be set up for use with any type of {{comm}} sent through Lamplight. They can include mail merge fields, which draw data directly from associated profiles or work records.

If you have not yet created any {{comm}}s templates, there will be two standard ones already in the table. **Do not delete these** — there must always be at least one template here in order to create others.

### To Add a New Template

- Go to 'admin -> system administration -> {{Comm}} Settings -> Manage {{comm}} templates.'
- You will see a table, either with example templates or with ones which have already been set up. 
- Right click on any row of the table or use a menu button in the left column to bring up a menu.
- Choose ‘Add new’.

![{{Comm}} Template Pop-up Menu](21.1.1a.png)

- Give your template a name, and a short description.
- You may see a 'Use {{comm}} roles with mail merge fields in this template?' box. If so, you can choose whether you want to be able to use merge fields relating to the {{comm}}s role you have assigned in the record. 
   - For example, you may have {{comm}} roles called 'service user' and 'referrer', and have added people with these respective roles to the attendance table of the {{comm}} record. When composing the {{comm}}, you can then use merge fields like this: "Dear 'referrer title' 'referrer surname', thank you for referring 'service user name' to us."
   - {{Comm}} roles in a template are used when you are sending a letter to a single recipient; others in the attendance table are just used for merge information drawn from their profiles.
   - For more on setting up {{comm}} roles, see [21.1.3 The {{Comm}} Module: {{Comm}} Roles](/help/index/p/21.1.3).
- Click the + symbol in the top, right-hand corner of the text box to reveal the text editing tools. This will allow you to apply formatting to the document, as well as including images and merge fields.

![Comm}} Form Expand Toolbar](21.1.1b.png)

- Enter the content of your template into the large text field. This could be the text of an email or letter, for example.
- If you paste text from another source, we'd recommend that you paste it into the box as plain text, either by using Ctrl+Shift+v in Windows, or pasting into Notepad first and then copying from there. This will take out any stray HTML from other programmes which could corrupt the formatting of your template.
- You can insert images from the {{comm}}s library using the ‘Image library’ menu. (For more on adding images to the library, see [21.1.4 {{Comm}}s Module Image Library](/help/index/p/21.1.4). 
   - Once inserted, you can choose to justify the picture left, centrally or right by selecting it with your mouse and using the text justification buttons. 
   - You can also add images from the web by clicking the small image icon in the ‘Insert’ section of the text editor and specifying the relevant url.
 - Once text and images are in place, format the {{comm}} using the options at the top of the text box, as in any document editor.

![Text Editing Tools](21.1.1c.png)

### Mail Merge Fields

Much like in a word processor, you can use mail-merge fields to include information from profiles and/or work records into your {{comm}}s.

   **Profile Mail Merge Fields**
   
- The ‘Body mail merge’ menu contains fields that can be inserted from profiles of people, organisations or volunteers. 
   
   ![Body Mail Merge](21.1.1d.png)
   
- When creating a template, make sure that you only select relevant options. For example, if you use fields relating to a volunteer in a template to partner organisations, those fields would be empty when merged, as this information would not exist in an organisation profile.
- Select the relevant merge field from the drop-down list and use it in the text as you would to normal content. For example, write ‘Dear (First name)’ by typing ‘Dear ’ and then selecting ‘Body Mail merge > Contact details > First Name’ from the drop-down menu. When you use this template to send a {{comm}}, (First name) will be replaced by the name of each person to whom you send the {{comm}}.
- If any recipient doesn’t have information in the field you used, the system will leave a single blank space.
   
   **{{Work}} Record Mail Merge Fields**
   
- If you choose ‘Communicate’ from the context menu of any activity type record, such as a {{work}} record, you’ll also see the option for ‘{{Activity}} merge’. This allows you to use mail merge fields using information contained in the activity record itself. 

![{{Activity}} Merge](21.1.1e.png)
   
### Nested Templates

{{Comm}} templates can be nested within each other. For example, a header containing logo and contact details can be saved as a template and then inserted into other {{comm}}s templates. To use one template within another: 
- Add a new template, as usual.
- Select the template that you want to use nest from the 'document template' drop-down. 

![Nesting Template 1](21.1.1f.png)

- It will be inserted where the cursor is placed.
- Carry on to complete your new template as normal. 

![Nesting Template 2](21.1.1g.png)

### HTML Checks

{{Comm}}s composed in {{Lamplight}} are formatted in HTML and it is possible to view them in HTML and run an HTML check.
It is only recommend to use this if you have an understanding of HTML. 

![HTML Checks](21.1.1h.png)

- The first button lets you view and edit the HTML content of your message directly. This can be useful for troubleshooting formatting issues. Click it again to return to a normal view. 
- The second button checks the HTML and filters it, if necessary. This filtering happens when you send or create the message, so clicking this button lets you double-check the content of your message beforehand. It can be useful to use this after pasting text from Microsoft Word, to check whether it behaves as expected. In some cases, where there is an issue, the message will become corrupted or seem to disappear. If this happens, delete the content of your message, then click the third button.
- The third button switches the MS filter on or off. When this is turned off (it's on by default) the editor will not run the filters, and the copied text will be sent as it is. This should be okay for emails, but it is very likely to cause problems if you are creating letters. Lamplight translates HTML into Rich Text Format but expects valid HTML to convert (which Microsoft code is not). If you need to send an unfiltered email, you may want to send a test first.

### Saving and Testing

- Once you have completed your template, click the ‘Save’ button in the bottom, right-hand corner. 
- Try using it and testing the formatting before returning to make additional changes.

### Editing or Deleting a Template

- Open the 'Manage {{comm}} templates' page. 
- Find the template you want, right click on it or click on the context menu to the left of it.
- Choose either 'Edit’ or ‘Delete’ options. 

![Edit and Delete Template Options](21.1.1i.png)

### Deleting a template will not affect any {{comm}}s already sent.

###### comms module


# 21.1.2 {{Comm}} Module: Adding, Editing and Deleting {{Comm}} Text  Templates

> A {{comm}} text template is typed directly into a {{Lamplight}} text box. Any database operator can then use it as often as they need rather than retyping the content each time. It is best for simple communications such as emails and SMS messages, which do not require too much formatting


Text templates can be created directly in the communications section of system administration, then used for any type of communication. 

### To Add a New Template

- Go to 'admin -> system administration -> {{Comm}} Settings -> Manage {{comm}} templates. You’ll see a table, either showing existing templates or with an example one. 
- Click the 'Add a new template’ button.

![Add new template](21.1.2d.png)

- Give your template a name, and a short description. The name is what database operators will see listed in the drop down menu when creating a new {{comm}}, so it should be as clear as possible.
- As this is a text template do not select a file. 
- Click the + symbol in the top, right-hand corner of the text box to reveal the text editing tools. This will allow you to apply formatting to the document, as well as including images and merge fields.

![Comm}} Form Expand Toolbar](21.1.1b.png)

- Enter the content of your template into the large text field. This could be the text of an email or letter, for example.

- If you paste text from another source, we'd recommend that you paste it into the box as plain text, either by using Ctrl+Shift+v in Windows, or by pasting it into Notepad first and then copying from there. This will take out any stray HTML which could corrupt the formatting of your template.

### Mail Merge Fields

Much like in a word processor, you can use mail-merge fields to include information from profiles and/or {{work}} records into your {{comm}}s.

#### Profile Mail Merge Fields
   
The ‘Body mail merge’ menu contains fields that can be inserted from profiles of {{people}}, {{org}}s or {{volunteer}}s. 
   
   ![Body Mail Merge](21.1.1d.png)
   
When creating a template, make sure that you only select relevant options. For example, if you use fields specifically relating to {{volunteer}}s in a template to partner {{org}}s, those fields would be empty when merged as this information would not exist in an {{org}} profile.
- Select the relevant merge field from the drop-down list and use it in the text as you would to normal content. For example, write ‘Dear (First name)’ by typing ‘Dear’ and then selecting ‘Body Mail merge > Contact details > First Name’ from the drop-down menu. 

[Choosing Body Mail Merge Fields](21.1.2e.png)

- When you use this template to send a {{comm}}, {{Lamplight}} will automatically '(First name)' replace this field with the name in each individual {{comm}} (although it will still  be saved in their records with '(First name)').

- If any recipient doesn’t have information in the field you used, {{Lamplight}} will leave a single blank space.
   
#### {{Activity}} Record Mail Merge Fields
   
{{Activity}} merge fields give you the option of using the information from {{activity}} records, for example {{work}} or {{referral}}s. 

![{{Activity}} Merge](21.1.2e.png)
(Please note, in the image above {{Activity}} is shown as {{Activity}} because of system customisation).

- To use these in your template, select the relevant fields from the ‘{{Activity}} merge’ dropdown menu.

- Make sure that your template has a name which indicates these fields have been used. For the information to be completed in your {{comm}}, you will need to have started by clicking on the ‘Communicate’ option in the context menu of the relevant {{activity}} record so that {{Lamplight}} knows which information to use. 

[Using a {{Comm}}s Activity Merge Template](21.1.2f.png)

For more on this see [21.3.1 Communicating with Everyone Attending a Particular {{Work}} Record](/help/index/p/21.3.1).

#### Using Communication Roles in Templates

You may use [{{comm}} roles](/help/index/p/21.1.6) in your system. If you do, you will be able to assign people roles in the ‘Recipients’ table of your {{comm}}s records. 

[Adding {{Comm}} Roles in the Recipients' Table](21.1.2g.png)

In this case, when you set up a new {{comm}} template you will be given the option to 'Use {{comm}} roles with mail merge fields in this template'. If you choose this option, you will be able to use profile information relating to the different people in the ‘Recipients’ table of the the {{comm}}.
For example, if as in the example above, you have the recipients' roles of 'service user' and 'referrer', you can use merge fields like this: "Dear 'referrer title' 'referrer surname', thank you for referring 'service user name' to us."  
To add them to the template, use the 'body mail merge' drop-down options. If you've chosen the option of using {{comm}} roles with mail merge fields, when click on an option (for example '(First name), a pop-up box will appear asking you which {{comm}} role that relates to.

[{{Comm}} Role Options in the Body Merge Drop-down](21.1.2h.png)

{{Lamplight}} will then enter the merge tag that you need into the template.

[{{Comm}} Role Field in {{Comm}} Template](21.1.2i.png)

These {{comm}} roles can only used when you are sending a letter to a single recipient.

For more on this see [21.1.6 {{Comm}}s Module: {{Comm}} Roles](/help/index/p/21.1.6).

#### Images
- You can insert images from the {{comm}}s library using the ‘Image library’ dropdown menu. (For more on adding images to the library, see [21.1.7 {{Comm}}s Module Image Library](/help/index/p/21.1.7).  
- Once inserted, you can choose to justify the picture left, centrally or right by selecting it with your mouse and using the text justification buttons.
- Double-clicking on the image will bring up a dialogue box where you can format the image's size, text-flow, padding and border.

[Picture Formatting Menu](21.1.2j.png)

- You can also add images from the web by clicking the small image icon in the ‘Insert’ section of the text editor and specifying the relevant URL.

   
### Nested Templates

{{Comm}} templates can be nested within each other. For example, a header containing a logo and contact details can be saved as a template and then inserted into other {{comm}}s templates. To use one template within another: 
- Add a new template, as usual.
- Select the template that you want to use nest from the 'document template' drop-down. 

![Nesting Template 1](21.1.1f.png)

It will be inserted where the cursor is placed.  Carry on to complete your new template as normal. 

![Nesting Template 2](21.1.1g.png)

### HTML Checks

{{Comm}}s composed in {{Lamplight}} are formatted in HTML and it is possible to view them in HTML and run an HTML check.
We would recommend that you only use this if you have an understanding of HTML. 

![HTML Checks](21.1.1h.png)

- The first button lets you view and edit the HTML content of your message directly. This can be useful for troubleshooting formatting issues. Click it again to return to a normal view. 
- The second button checks the HTML and filters it, if necessary. This filtering happens when you send or create the message, so clicking this button lets you double-check the content of your message beforehand. It can be useful to use this after pasting text from Microsoft Word, to check whether it behaves as expected. In some cases, where there is an issue, the message will become corrupted or seem to disappear. If this happens, delete the content of your message, then click the third button.
- The third button switches the MS filter on or off. When this is turned off (it's on by default) the editor will not run the filters, and the copied text will be sent as it is. This should be fine for emails, but it is very likely to cause problems if you are creating letters. Lamplight translates HTML into Rich Text Format but expects valid HTML to convert (which Microsoft code is not). If you need to send an unfiltered email, you may want to send a test first.

### Finishing Your Template

Once text and images are in place, format the {{comm}} using the options at the top of the text box, as in any document editor.

![Text Editing Tools](21.1.1c.png)

### Saving and Testing

When you’re happy with your template, click the ‘Save’ button in the bottom right-hand corner.  Try creating a new {{comm} record to test the formatting. See [21.3.0 Creating and Logging {{Comm}}s](/help/index/p/21.3.0) for more information on this.
If you find the template isn’t exactly as you wanted, you can come back to make additional changes (see ‘Editing’ below).

If you’d rather test as you go, we suggest that you create a regular {{comm}} record with the content you need, then choose 'test' to see how it looks while keeping the editor open.  Once you’re happy with your content you can copy and paste it into the {{comm}} template (it's most reliable to copy the html).

### Editing or Deleting a Template

- Open the 'Manage {{comm}} templates' page. 
- Find the template you want, right click on it or click on the context menu to the left of it.
- Choose either 'Edit’ or ‘Delete’ options. 
**Deleting a template will not affect any {{comm}}s that have already been sent.**

![Edit and Delete Template Options](21.1.1i.png)


###### comms module

# 21.1.3 {{Comm}} Module: Adding, Editing and Deleting {{Comm}} Word File Templates

> A {{comm}} Word file template is pre-formatted in Microsoft Word, then uploaded into {{Lamplight}}. It allows for more complex formatting of forms and letters


Word file Templates are created in Microsoft Word and then uploaded into {{Lamplight}}.  You can use mail-merge tags by entering the specially formatted placeholders in the Word doc. {{Lamplight}} will then recognise these and replace them with the relevant data each time you use the template.  [Section 21.1.6 has a list of all the tags](/help/index/p/21.1.6) you can use in your files.

### File Format

You should create your file as a standard .docx Word file rather than a Microsoft Word template, and format it as usual.
Once you have uploaded your template to Lamplight you will not be able to edit it in the database, so we recommend storing a separate copy on your computer of shared drive. If you need to make any changes in future you can amend the copy, then upload the updated version to {{Lamplight}}. 

### Formatting for Multiple Copies

If you want to generate multiple copies of a document (e.g. a number of mail merge letters that you will print out and post), you will need to add 'repeat blocks' to the template.  These tell {{Lamplight}} which part of the document to repeat for each one.  There are two ways to do this, either using ${repeat_template} or ${repeat_row}, but you can't use both in a single template.

**repeat_template**

When you have a large chunk of text to repeat, for example form letters for mail merge, ${repeat_template} is best.
- Put '${repeat_template}' at the start of the letter text
-Put '${/repeat_template}' (note the forward slash) at the end. 
 {{Lamplight}} will make a copy of the text between the tags for each recipient, with the merge information substituted into each copy.

**repeat_row**

If you have a table, and need each row of the table to include information for a different recipient’s profile, use the ${repeat_row} tag. 
- Add the ${repeat_row} tag  in first cell of each row of the table. 
This can be used to produce a list of contact details, for example, and creates a template with a table something like this:

| Name                                   | Phone    | Email    | Mobile    |
| :------------------------------------- | :------- | :------- | :-------- |
| ${repeat_row} ${First name} ${Surname} | ${Phone} | ${Email} | ${Mobile} |

a row will be added to the table for each recipient, and the ${repeat_row} text removed.

### Inserting Mail Merge Tags

Mail merge tags can be used to tell {{Lamplight}} to insert some of the information held in the database into the letter or document. Tags need to be set up in this format:
-  ${Field name} - a dollar symbol immediately following by curly braces and the field name.  For example, 'first name' would be ${First name}.
These are not Microsoft ‘fields’ - they are just text typed in.  You do not need to use Microsoft's mail merge or field menus to add these tags to your template.

You need to be particularly careful about two things:
- Make sure that you enter the field names exactly, paying particular attention to capitalisation, spelling and spaces , which all need to appear exactly as they do in [section 21.1.6](/help/index/p/21.1.6) or, in the case of custom profile fields, as they appear in your system.  You may wish to [download your system settings](https://lamplight.online/en/admin/uploadfields/type/get_settings) into a spreadsheet that you can copy and paste from.
- If you are formatting a mail merge tag, as bold for example, either format the whole tag or none of it - do not partially-format it as this will stop it from working. For example ${*First* name} would fail (the ** indicate bold here), because the extra formatting breaks up the tag.  {{Lamplight}} will look for '${First name}' in the file, but it will find something like '${!hey word show this bold!First!ok stop bold now! name}'.  So a search for ${First name} will fail. 

As a general rule, it will be best to create your document without mail merge tags first, then apply formatting, and then finally type in the merge tags you need.

#### Profile Tags

You can insert mail merge tags for the primary recipient. These tags will look like ${First name} ${Surname}, of ${Address line 1}.  
You might also want to use merge tags for linked profiles. These are not switched on in all systems, but if they are you will see names linked to other names when you type in the search box. For example, you might see 'Matthew Parker, Lamplight Database Systems Ltd'. This means that ‘Matthew Parker’ is the primary recipient, and 'Lamplight Database Systems Ltd' is the linked relationship.
If you are adding fields for the linked profile, they will have the word 'Linked' inserted into the tag: ${Linked First name} ${Linked Surname} of ${Linked Address line 1}.

#### Custom Field Tags

If you have custom fields in your profile tabs, you can use these in the Word template by entering the custom field name within ${} tags.  So to insert the 'Date of birth' value, you'd add ${Date of birth} as your merge tag.  These need to be typed in exactly as they appear within your system.

Note that {{Lamplight}} can only insert data in the fields you’re using if they match the profile type you’re sending to.  For example, if you have a field in {{org}} profiles called 'Turnover' and you insert it in a template for a letter out to {{user}} profilesI , the merge tag will be left in the letter because it doesn’t match any fields in the {{user}} profile.

You also need to make sure that all the fields in your system have a unique name. If you have two with the same name you will get unpredictable results, as {{Lamplight}} will not know which one you’re referring to.

Custom field names with $, { or } in them may also result in unpredictable results and should be avoided.

### Inserting Information from the Profile of the Person Creating the {{Comm}}

You can use merge tags to use information relating to the member of staff generating the record. If you add 'me|' to the front of the field name {{Lamplight}} will use the database operator’s profile to complete the merge.  For example, you could include "please contact me on ${me|Phone}" or sign off your letter with a footer:

Yours,

${me|First name} ${me|Surname}

${me|Email}
${me|Phone}

(The vertical line symbol - | - is called a 'pipe' and is usually on the key next to the z on your keyboard).
This can save time if you will have multiple members of staff using the same Word templates.

### {{Activity}} Tags

You can also insert merge fields from {{activity}} records. This template can be used by generating the {{comm}} record from a particular {{activity}} where the recipients will be the attendees of the {{activity}} (see 21.3.1 Communicating with Everyone Listed on a Particular {{Work}} Record](/help/index/p/21.3.1). You can include details such as the date, time, summary text, grant amounts etc. from the record.

### {{Comm}} Role Tags

{{Comm}} roles can be used when you wish to generate a single document from multiple profiles.  For example you might write to a GP (who has their own profile) and include information from a {{user}}’s profile. In this instance you can use {{comm}} roles to tell {{Lamplight}} which profile to use for which mail merge tags.

First of all you would need to [set up {{comm}} roles](/help/index/p/21.1.3) for 'GP' and 'user', and note down their IDs (you can see the ID number in the table once the role has been saved).  For this example let's say the role 'GP' has ID 5 and 'user' has ID 12.

The letter will be addressed to the GP and refer to the user, so your template starts:

Dear Dr ${commsrole5|Surname},

*Re. ${commsrole12|First name} ${commsrole12|Surname}, dob: ${commsrole12|Date of birth}.*

You add the identifier 'commsrole5|' for the GP (as GP is role ID 5) and 'comssrole12|' for the user (as 'user' is role ID 12) to the merge tags so the {{Lamplight}} looks for the information in the correct profiles.

If you are using {{comm}}s roles in a template, we'd strongly recommend you note this in the name or description of the template when you upload it, so that you and others are aware of this when they use the template.  See [section 21.1.3](/help/index/p/21.1.3) for more on how to generate a {{comm}} using {{comm}} roles.

### Uploading Your Template

To upload a Word file template:
- Go to admin > system administration > Communication Settings > Manage communication templates.
- You will see a table, either with example templates or with ones which have already been set up. 
- Click the 'add a new template button'.
- Give your template a name, and a short description.
- Find the Word file template in your computer's directory, then click 'save'.  
 
### Using Your Templates

When creating a {{comm}}, your Word file Templates will be listed below the main text editor on the 'Content' tab.  Ignore the text editor and select the file you wish to use from the list.  The text will not show up in the text editor, but the merged document will be downloaded, and a copy will be saved to the profile of each recipient.



###### comms module


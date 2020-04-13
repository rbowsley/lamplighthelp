# 21.1.5  {{Comm}} Module: creating Word file Templates.

> Word file templates are Microsoft Word files that you upload into {{Lamplight}} to use as mail-merge templates to generate Letters and Documents.

You create Word file Templates in Microsoft Word and then upload them into {{Lamplight}}.  They need to include specially formatted placeholder tags, which {{Lamplight}} will replace with data from your system when you come to use the template.  [Section 21.1.6 has a list of all the tags](/help/index/p/21.1.6) you can use in your files.

### File format

You should save your file as a standard .docx Word file.  It shouldn't be a Microsoft Word template.  Once you have created your template and uploaded it you won't be able to edit the template, you can only replace it, so we recommend storing a copy of the source template files on your system.

### Inserting mail merge tags

Mail merge tags in Word files have to look like this: ${Field name} - a dollar symbol immediately following by curly braces and the field name.  So to insert a 'first name' field you would type ${First name}, for example.

These are not 'fields' in Microsoft terminology - they are just text typed in.  You do not need to use Microsoft's mail merge or field menus and functionality to add the mail merge tags.

There are two aspects that require particular care when entering the tags:

- Ensure that you enter the field names exactly.  Capitalisation, spelling, spaces - all need to appear exactly as they do in [section 21.1.6](/help/index/p/21.1.6), or in the case of custom profile fields, as they appear in your system.  You may wish to [download your system settings](https://lamplight.online/en/admin/uploadfields/type/get_settings) into a spreadsheet that lists all your fields and settings, that you can copy and paste from.
- Do not partially-format a mail merge tag.  If you type in your mail merge tag and then apply formatting to only part of it, the tag will no longer work.  For example ${*First* name} would fail, because the extra formatting breaks up the tag.  {{Lamplight}} will look for '${First name}' in the file, but what is there is actually something like '${!hey word show this bold!First!ok stop bold now! name}'.  So a search for ${First name} will fail.  Even if this could be overcome, it's not clear whether you'd want the name to appear bold or not.

As a general rule, it will be best to create your document without mail merge tags first, then apply formatting, and then finally type in the merge tags you need.

### Profile tags

You can insert mail merge tags for the primary recipient, and any related profile.  These tags will look like ${First name} ${Surname}, of ${Address line 1}.  The fields for the related profile will have the word 'Linked' inserted into the tag: ${Linked First name} ${Linked Surname} of ${Linked Address line 1}.


### Custom field tags

To insert data from the primary recipient's profile custom tabs, you simply enter the custom field name within the ${} tags.  So to insert the 'Date of birth' value, you'd add ${Date of birth} as your merge tag.  These need to be typed in exactly as they appear within your system.

Note that {{Lamplight}} will only insert data for fields that a particular profile can have.  For example, say you have a field called 'Turnover' that appear on {{org}} profiles, and insert the ${Turnover} tag in you document.  If you use that template with a {{user}} profile, the merge tag will be left in the document because it can't be matched to fields in the {{user}} profile.

You also need to make sure that you don't have fields with the same name, or the same names as any of the built-in merge tags, or you will get unpredictable results.

Custom field names with $, { or } in them may also result in unpredictable results and should be avoided.


### Inserting information from the profile of the person creating the {{comm}}.

You can use merge tags to personalise the document from the member of staff generating the record.  If you add 'me|' to the field name {{Lamplight}} will use the staff profile.  So you can include things like "please contact me on ${me|Phone}" or sign off your letter with a footer:

Yours,

${me|First name} ${me|Surname}

${me|Email}
${me|Phone}

(The vertical line symbol - | - is called a 'pipe' and is usually on the key next to the z on your keyboard).



### {{Activity}} tags

As with Text templates, you can insert merge fields from {{activity}} records. If you generate the {{comm}} record from a particular {{activity}} the recipients will be the attendees of the {{activity}}, and you can include things like the date, time, summary text, grant amounts etc. from the record.


### Repeating blocks.

If you want to generate multiple copies of a document (e.g. mail merge letters you want to print out and post), you will need to add 'repeat blocks'.  These tell {{Lamplight}} which part of the document to repeat for each profile.  There are two tags you can use to do this: ${repeat_template} and ${repeat_row}, but you can't use both in a single template.

#### repeat_template

${repeat_template} is used to repeat a large chunk of text - for example form letters for mail merge.  You need to put '${repeat_template}' at the start of the letter text, and '${/repeat_template}' (note the forward slash) at the end.  {{Lamplight}} will make a copy of the text between the tags for each recipient, with the merge information substituted into each copy.

#### repeat_row

The ${repeat_row} tag is used in tables, where you want each row in the table to include information from a different recipient profile.  You could use this to produce a list of contact details, for example, by creating a template with a table something like this:

| Name                                   | Phone    | Email    | Mobile    |
| :------------------------------------- | :------- | :------- | :-------- |
| ${repeat_row} ${First name} ${Surname} | ${Phone} | ${Email} | ${Mobile} |

a row will be added to the table for each recipient, and the ${repeat_row} text removed.



### {{Comm}} role tags

{{Comm}} roles can be used when you wish to generate a single document from multiple profiles.  For example you might write to a GP (who has their own profile) with information from a {{user}}s profile.  You don't want two letters, one for the GP and one for the {{user}}: you want a single letter.  You use {{comm}} roles to tell {{Lamplight}} which profile to use for which mail merge tags.

First of all you would need to [set up {{comm}} roles](/help/index/p/21.1.3) for 'GP' and 'user', and note down their IDs.  For this example let's say role 'GP' has ID 5 and 'user' has ID 12.

You want to address the letter to the GP and reference the user, so your template starts:

Dear Dr ${commsrole5|Surname},

*Re. ${commsrole12|First name} ${commsrole12|Surname}, dob: ${commsrole12|Date of birth}.*


In the merge tags we add the identifier 'commsrole5|' for the GP (as GP is role ID 5) and 'comssrole12|' for the user (as 'user' is role ID 12).

If you are using {{comm}}s roles in a template, we'd strongly recommend you note this in the name or description of the template when you upload it, so that you and others are reminded when you comm to create the {{comm}}.  See [section 21.1.3](/help/index/p/21.1.3) for more on how to generate a {{comm}} using {{comm}} roles.






### Uploading your template

Word file templates need to be uploaded to {{Lamplight}} in system admin - [instructions are in 21.1.1](/help/index/p/21.1.1).


### Using your templates

When creating a {{comm}}, your Word file Templates will be listed below the main text editor on the 'Content' tab.  Ignore the text editor and select the file you wish to use from the list.  The merged document will be downloaded, and saved to the profiles of all recipients.



###### comms module
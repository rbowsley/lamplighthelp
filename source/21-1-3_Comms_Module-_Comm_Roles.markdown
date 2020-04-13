# 21.1.3 {{Comm}}s Module: {{Comm}} Roles

> {{Comm}} roles mean that you can assign different roles to {{people}} and {{org}}s involved in {{comm}}s. These are like roles in {{activity}} record attendance tables, and are used to generate advanced mail merges

### Why Use {{Comm}} Roles?

Ordinarily, if you create a mail-merge letter, a copy is created for each recipient listed. Their details will be substituted into the document wherever you have data placeholders.

Sometimes it is useful to be able to combine data from several profiles into a single document. For example, you may need to write to a parent using data from both their profile and their child's. Or you may be writing a letter on behalf of a client and their carer. In these circumstances you want a single document with the relevant names and data in the right place. This is when you use {{comm}} roles.  {{Comm}} roles are the way that {{Lamplight}} uses to determine which profiles information goes where.  They are best when you need to send a similar {{comm}} and can set up a {{comm}} template containing the merge fields.

### Creating a {{comm}} using {{comm}}s roles

When creating the {{comm}} add recipients as normal, but additionally select the relevant role for each profile in the table. When adding merge fields to your {{comm}} content, you specify which role each mail merge field is getting the information from. So instead of mail-merge fields like [first name], you would have [parent first name] and [child first name].

![{{Comm}} Roles in a {{Comm}}s Record](21.1.3a.png)

Once you have selected the roles, you also need to change 'Combine to single {{comm}}?' below the table, to 'Produce a single letter, using mail-merge fields based on {{comm}} role'.

In the message content section, select the template or enter your message content as normal.  If you do add any merge fields in the text editor, you will be prompted to select which {{comm}}s role the field is for.

### Adding, Editing and Deleting {{Comm}} Roles

The process for adding, editing and deleting communication roles is the same as that for [adding types of logged communication](/help/index/p/21.1.2). Click on the link for more details. 


###### comms module

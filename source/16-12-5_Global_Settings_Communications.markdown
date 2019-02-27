# 16.12.5 Global Settings: Communications

> In the section the System Administrator can specify the reply address for SMS (if you have it) and email, allow {{Lamplight}} to store international mobile phone numbers in the contact details tab, and decide some default communications settings. If you have the communications module, you can also set up a link to Mailchimp here

The fields in the communications tab are:

- **Default reply-to email address**

   Unless an email address is specified here, replies to emails sent using {{Lamplight}} will be sent to the email address of the person sending the communication, i.e. the address they use to log into Lamplight. An email address entered in this box will be used instead, and this will apply to all users. If you want all replies to be addressed to a central email inbox, specify it here.
   
- **Default reply-to mobile number (for SMS)**

   This option allows a telephone number to be specified for replies to SMS messages sent through Lamplight.

- **Allow international mobile phone numbers?**

   By default, mobile phone numbers are expected to be UK mobile numbers, and it is not possible to save invalid numbers. Selecting this option means that mobile numbers must instead be formatted in the international style (e.g. +44 79XX XXXXXX).
   
- **Staff member to receive unsubscribe notifications**

   When emails are sent through {{Lamplight}} an unsubscribe link is appended to all messages. If this is clicked, the staff member specified will receive a task notifying them that the profile has asked to be removed from the mailing list.
   
- **Include your signature automatically at the bottom of new {{comm}}s?**

  If this option is enabled, the database operator’s name will automatically be added to the message content when creating new {{comm}}s, saving them from typing it at the end of each {{comm}}.
  
- **Show date and work area on communications?**

   This option governs whether date and work area are to be specified for each {{comm}}. These appear in the ‘New {{comm}}’ page as shown here.
   
   xxxxxxx Picture here xxxxxx
 
   These options provide criteria for filtering information when reporting on {{comm}}s. If this functionality is not required, the options for new {{comm}}s can be simplified by disabling this option.

- **Add me to blank or individual communications?**

   This option governs whether the profile of the database operator creating a {{comm}} will be added as a recipient to {{comm}}s created using {{work}}>{{comm}} in the main menu or from the contextual menu of a record, such as a {{work}} record, as shown below.
   
   xxxxxx Picture here xxxxxx
 
   The database operator will not be added to a {{comm}} created using the right-click contextual menu from a group (unless their profile is among those in the group), as shown in this image.
   
   xxxxxx picture here xxxxxx
 
   If the option is disabled, the database operator’s profile will not be added automatically to any new communications.
   
- **Add a {{message}} tab to {{comm}}s?**

   This option adds a ‘{{Message}}’ tab to {{comm}}s so tasks can be associated with {{comm}}s as they might be other types of record. It appears as shown below.
   
   xxxxxx picture here xxxxxx
 
- **Default address block/text to use when creating mailing labels:**

   This field allows you to specify the text that is automatically added to the message content field when creating mailing labels. This would usually consist of merge fields. If this field is left blank, the default content is as shown below.
   
   xxxxxx picture here xxxxxx
 
- **Default mailing label size**

   When creating mailing labels, there is a tab that allows you to specify the type of label, from a list of standard Avery sizes.
 
   If you know that database operators will usually use the same size label, it can simplify the process to set a default size using this option.
   
   
   ...MAILCHIMP AND CAMPAIGN MONITOR SECTIONS NEED ADDING...
   
   
   ###### core module

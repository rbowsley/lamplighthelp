# 16.11.5  <i class="fas fa-envelope-open"></i> Setting Up Outlook Emails With Your Own Server (Not Office 365)

> Instructions for setting up email in {{Lamplight}} if you have an Outlook account hosted on your own server



This is how to enter the correct settings in Lamplight if you are using Outlook with your own email server.

To be able to set this up, you will need to know your server details. To find this in your Outlook account:

- In the Outlook menu, choose File, and select ‘Account settings’.

![Outlook Account Settings](16.11.5a.png)

- Choose the options ‘Account settings’ from the drop-down.
- This will show you a pop-up box, showing your accounts.  
- Double click on the one that you want to show the account information. 

![Outlook Settings](16.11.5b.png)

### Entering Settings in Lamplight

From the main menu, go to 'admin -> system administration'.  Under ‘Communication Settings’ you'll see two options:
   - Email settings: to send via a single email account for all operators. You can use this as a default for all operators if you want to. Once you have set this up, anyone without an individual operator email account will still be able to send emails from this one.
   - Email settings: to send via individual operator email accounts. Use this option to have different settings for individual users.

Whichever you are setting up, you will need to complete the following fields for each email account you add:

![Lamplight Settings](16.11.1c.png)

Use the information that you've just gathered to fill in these fields. The password will be the password for the email account.

- If you’re setting up individual operators, you may wish to ask them to enter their password directly into the form.  
- Save when complete.  
- Repeat this for each account you need to add.
  
### Email Sending Limits

There are some limits on how many emails you can send with some accounts.  

If you need to send more emails than your provider allows you can use MailChimp with Lamplight. See [21.2.0 {{Comm}}s: Linking with Mailchimp](/help/index/p/21.2.0) for more details. 


###### core module

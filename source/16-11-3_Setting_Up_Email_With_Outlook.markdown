#    16.11.3 Setting Up Email With Office 365

> Instructions for setting up email in {{Lamplight}} if you have an Outlook account

To set up emails in Lamplight, you enter your server details, and your Outlook password to allow Lamplight access to your account.

- From the main menu, go to 'admin -> system administration'.
- Under ‘Communication Settings’ you'll see two options:
   - Email settings: to send via a single email account for all operators. You can use this as a default for all operators if you want to. Once you have set this up, anyone without an individual operator email account will still be able to send emails from this one.
   - Email settings: to send via individual operator email accounts. Use this option to have different settings for individual users.
- Whichever you are setting up, you will need to complete the following fields for each email account you add:

[Lamplight Settings](16.11.1c.png)

Host name: smtp.office365.com.  
Port: 587.  
Authentication: login.  
SSL type: TLS.  
Username: your email address.  
Password: your Outlook password (which you use to access your Office 365 account).  

- If you’re setting up individual operators, you may wish to ask them to enter their password directly into the form.  
- Save when complete.  
- Repeat this for each account you need to add.

  
### Email Sending Limits

There are some limits on how many emails you can send with some accounts.  Each type of Office 365 account is different, and we advise you check your account.  
If you need to, you can use MailChimp with Lamplight. See [21.2.0 {{Comm}}s: Linkiing with Mailchimp](/help/index/p/21.2.0) for more details. 




###### core module

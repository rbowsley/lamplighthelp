# 16.11.6  <i class="fas fa-envelope-open"></i> Setting Up Email With Other Common Providers

> Instructions for setting up email in {{Lamplight}} if you have an account with another provider



### Identify Your Server Details

You will need SMTP connection settings for your email server in order to send emails through it.  This information is not available to us at Lamplight, you'll need to find it:

- Check our list of common providers at the bottom of this page - you may find the settings there.
- Ask your IT support if you have it.
- Ask your email provider - you may find this information in the provider’s help system.  

There are detailed instructions for [Outlook and Gmail](/help/index/p/16.11.0) in this  manual.

#### What You’ll Need to Know

- The server: e.g. smtp.mail.example.com
- The SMTP port: e.g. 587
- The security method : e.g. TLS
- Authentication method: (Normally login)
- Your username: e.g. me@myemail.com
- Your email password.

### Entering Settings in Lamplight

From the main menu, go to 'admin -> system administration'.  Under ‘Communication Settings’ you'll see two options:

   - Email settings: to send via a single email account for all operators. You can use this as a default for all operators if you want to. Once you have set this up, anyone without an individual operator email account will still be able to send emails from this one.
   - Email settings: to send via individual operator email accounts. Use this option to have different settings for individual users.
- Whichever you are setting up, you will need to complete the following fields for each email account you add:

![Lamplight Settings](16.11.1c.png)

Use the information that you've just gathered above to fill in these fields. The password will be the password for the email account.

- If you’re setting up individual operators, you may wish to ask them to enter their password directly into the form.  
- Save when complete.  
- Repeat this for each account you need to add.
  
### Email Sending Limits

There are some limits on how many emails you can send with some accounts.  
If you need to send more emails than your provider allows you can use MailChimp with Lamplight. See [21.2.0 {{Comm}}s: Linking with Mailchimp](/help/index/p/21.2.0) for more details. 

### Settings for Some Common Email Providers

| **Provider** | **SMTP** | **Port** | **Authentication** | **Security** |
| ------------ | -------- | -------- | ------------------ | ------------ |
| AOL | smtp.aol.com | 465 | Login | SSL |
| BT Internet | mail.btinternet.com | 465 | Plain | SSL |
| GMX Mail | mail.gmx.com | 587 | Login | SSL |
| Hotmail | smtp.live.com | 587 | Login | SSL |
| iCloud | smtp.mail.me.com | 587 | Login | TLS |
| Plusnet | relay.plus.net | 587 | Plain | SSL |
| Virgin | smtp.virginmedia.com | 465 | Login | SSL|
| Yahoo | smtp.mail.yahoo.com | 487 | Login | TLS|
| Yandex | smtp.yandex.com | 465 | Login | SSL |
| Zoho Mail| smtp.zoho.com | 587 | Login | TLS |

(These were correct as of May 2019 but may change - please check with your email provider if you're having problems.

###### core module


# 16.11.2 Setting Up Gmail With Two Factor Authentication

> Instructions for setting up email in {{Lamplight}} if you have a Gmail account with two factor authentication activated

### Generating a Google Password

When using 2 factor authentication, you don’t enter your Gmail password into Lamplight.  Instead you ask Google to generate a unique password key, just for Lamplight.

- In Gmail, select the menu icon in the top right  (9 small dots). 
- Select the 'Account' option from the drop-down menu.

![Google Account](16.11.2a.png)

- Choose ‘Security’ from the left-hand menu.  
- You’ll see a section titled ‘Signing into Google’. In this section, select ‘App passwords’.  
- Gmail will ask you to confirm your password, and will take you to a screen to generate a password.

![Google Password Box](16.11.2b.png)

- Choose the option called ‘select app’, and ‘Other (custom name)'.  
- In the box which pops up, type Lamplight (or whatever you want to identify this app password by).  
- Press the ‘Generate’ button. You’ll see a screen like this:

![Google App Password](16.11.2c.png)

- Copy this password right away - this is the only time you'll see it. 
- Once you have used this password to set up Lamplight you won't need it again and can destroy it.

### Entering Settings in Lamplight

- Go to 'admin -> system administration -> Communication settings'.
- In here you have two options:
   - Email settings: to send via a single email account for all operators. You can use this as a default for all operators if you want to. Once you have set this up, anyone without an individual operator email account will still be able to send emails from this one.
   - Email settings: to send via individual operator email accounts. Use this option to have different settings for individual users.
- Whichever you are setting up, you will need to complete the following fields for each email account you add:
  
[Lamplight Settings](16.11.1c.png)
  
  -  Host name: smtp.gmail.com.
   - Port: 587.
   - Authentication: login.
   - SSL type: TLS.
   - Username: email address.
   - Password: the App password you generated.
   
 - If you’re setting up individual operators, you may wish to ask them to enter their password directly into the form.
 - Save when complete.
 - Repeat this for each account you need to add.

### Email Sending Limits in Gmail

There are some limits on how many emails you can send with Gmail. The current limits are set out here: https://support.google.com/a/answer/166852?hl=en


###### core module

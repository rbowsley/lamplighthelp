# 16.11.1 Setting Up a Gmail Account

> Instructions for setting up email in {{Lamplight}} if you have a Gmail account



### Step 1: Tell Gmail to Allow Lamplight

You need to set Gmail to allow Lamplight to send emails via your Gmail account:
- Log in to your Gmail account.
- Click on the ‘Google apps’ menu in the top-right corner.
- Click on ‘My Account’.

!['My Account' in Google](16.11.1a.png)

- Click ‘Sign-in & security’.
- Scroll down to the ‘Connected apps & sites’ section. You will see ‘Allow less secure apps’ (it will probably be OFF).
- Click the slider to turn this on. 

![Allow Less Secure Apps Slider](16.11.1b.png)

- If you do not see the ‘Allow less secure apps’ box, your Google Administrator may need to enable it.  They will need to:
- Log in to Gmail.
- Click the cog in the upper-right corner, then ‘Manage this domain’.
- Click the ‘Security’ logo.
- Click ‘Basic settings’.
- Click ‘Go to settings for less secure apps’.
- Click ‘Allow users to manage their access to less secure apps’.
- Click ‘Save’.
- You will now be able to go back to the section above and allow less secure apps in your account.
- (Changes in Google domains may change the exact pathway to these settings, but they will normally continue to be available in the Security area.)

#### An Alternative to Allowing Less Secure Apps  

Your primary alternative is to use 2 factor authentication, and we recommend this.  However, if you don’t wish to allow less secure apps or use two factor authentication, there is a work around.  You can:
- Turn on two factor authentication for an individual's account, and set it up.
- Use our other guide (Gmail with 2FA) to generate a unique ‘App password’ and set-up Lamplight.
- Turn two factor authentication back off in Google, but the unique ‘App password’ will continue to function.

### Step 2: Enter Settings in Lamplight

As you are not using 2 factor authentication, you allow Lamplight access to your Gmail server by entering the server details and your email password.  This allows Lamplight access to send emails from your account.

- Go to 'admin -> system administration -> Communication settings'.
- In here you have two options:
   - Email settings: to send via a single email account for all operators. You can use this as a default for all operators if you want to. Once you have set this up, anyone without an individual operator email account will still be able to send emails from this one.
   - Email settings: to send via individual operator email accounts. Use this option to have different settings for individual users.
- Whichever you are setting up, you will need to complete the following fields for each email account you add:
  
[Lamplight Settings](16.11.1c.png)
  
- The details you will need are:
   - Host name: smtp.gmail.com.
   - Port:	587.
   - Authentication: login.
   - SSL type: TLS.
   - Username: email address.
   - Password: Your Gmail / Google password.
- If you’re setting up each operator individually, you need to repeat this for each operator.
- Save when complete.


### Email Sending Limits in Gmail

There are some limits on how many emails you can send with Gmail. The current limits are set out here: https://support.google.com/a/answer/166852?hl=en


###### core module

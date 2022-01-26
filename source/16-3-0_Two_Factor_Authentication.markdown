# 16.3.0 <i class="fa fa-cogs"></i> Two Factor Authentication

> Enabling two factor authentication adds a layer of protection to the log-in process


Two factor authentication adds a layer of protection to the login process. When set up, an app on your phone generates a 6-digit code every 30 seconds, which is only valid for 30 seconds. To log in you must enter your username/password followed by this 6-digit code. While it does add an extra step to the login process, the security benefits are significant.

### Adding 2FA to Your Account

First install an app on your phone (see links to app store versions of the Authenticator app below), or simply search for 'Authenticator App' in your app store: 
  - Google Play: [https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_GB](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_GB).
  - Windows Marketplace: [https://www.microsoft.com/en-gb/store/p/authenticator/9wzdncrfj3rj?rtc=1](https://www.microsoft.com/en-gb/store/p/authenticator/9wzdncrfj3rj?rtc=1).
  - Apple App Store: [https://itunes.apple.com/gb/app/google-authenticator/id388497605?mt=8](https://itunes.apple.com/gb/app/google-authenticator/id388497605?mt=8).

Once you have the app installed and working, 
- Go to 'system admin -> Database Operators and Security'.
- Click on 'Enable two-factor authentication and regenerate secret'.  
- At the bottom of the page is a 'Click here to generate a new secret' button. Click on this. 
- {{Lamplight}} will generate a secret code that you need to enter in the app on your phone.
- You’ll only need to enter this into your phone once. 
- When this is done, every time you log in to {{Lamplight}} you will see a new screen.

![2FA Login Screen](16.3.0a.png)

- Go to the app on your phone and find the six-digit code.
- Enter this and you will be logged in to {{Lamplight}} as normal.

### Removing 2FA From Your Account

If your phone is lost or stolen, you should ask your System Administrator to reset two-factor authentication for your login as soon as possible.  
- Go to 'system admin -> Database Operators and Security -> Manage database operators'.
- From the table of operators, find the name of the person who wants to remove 2FA and right click on it.
- Choose 'Remove two-factor authentication' from the menu.
- You can then set up two factor authentication again, which will generate a new shared secret.  

### Checking 2FA

To verify which operators have 2FA enabled:
- Go to 'system admin -> Database Operators and Security -> Manage database operators'.
- Check the 'Two factor authentication enabled' column in the database operators table, as shown in the screenshot below.

![2FA Table Column](16.3.0b.png)


##### Tags
Advanced topics
GDPR
Security

###### core module

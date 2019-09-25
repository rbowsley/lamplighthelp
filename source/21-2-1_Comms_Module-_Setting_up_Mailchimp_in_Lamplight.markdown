# 21.2.1  {{Comm}}s Module: Setting up Mailchimp in {{Lamplight}}

> Before you begin using Mailchimp, set up the details in system administration so that the two systems can talk to each other



The first thing that you will need to do is set up a Mailchimp account. Please make sure that you comply with their terms: [http://mailchimp.com/legal/terms/](http://mailchimp.com/legal/terms/).

### Setting Up a Mailchimp Account

Go to their sign-up page: [https://login.mailchimp.com/signup/](https://login.mailchimp.com/signup/) and follow their setup wizard. You will need to give details of your public website as part of this - if you do not have a website you can enter the address of your social media feed, for example Twitter or Facebook. Please do not use the Lamplight address.

### Linking Mailchimp to {{Lamplight}}

Your API key is similar to (but not the same as) a username and password that one computer program uses to identify itself to another, and this is what is used to link {{Lamplight}} to Mailchimp. 

#### Finding the API Key in Mailchimp
- Click on your name in the top right of the Mailchimp screen.
- Select ‘account’ from the drop-down menu.
- Choose ‘Extras’, and ‘API keys’. 

![API Key in Mailchimp](21.2.1a.png)

- Click on  ‘Create a key’ (under ‘Your API keys’). 
- Copy this key and open {{Lamplight}}.

#### Entering the API Key in {{Lamplight}}
- From the main Lamplight menu, choose ‘admin -> system administration’.  
- Under the 'Customise {{Lamplight}}' section, choose ‘Change global settings’.
- Once this page is open, click on the ‘Communications’ tab at the top.  

![MailChimp API](225a.PNG)

- Scroll down to the ‘Mailchimp’ section.  (If this isn’t here, you’ll need to ask us to activate Mailchimp in your system.)  
- Enter the API key in the field ‘MailChimp API key’.  
- Click save to store the API key.  {{Lamplight}} can then use this to complete the setup.

### Complete the setup: Mailchimp Options in {{Lamplight}}

You need to set-up your Mailchimp options on this page.
- Choose the 'audience' in Mailchimp that you want to use with {{Lamplight}}.  Please note that to ensure consistency once it is set it cannot be changed.  
- Default {{workarea}} to flag Mailchimp campaigns with: this field lets you choose which {{workarea}} Mailchimp emails will be logged against.  When you send the email in Mailchimp a copy will be sent to {{Lamplight}} to be stored in the {{comm}}s tab in a profile.
- Default {{comm}} type to flag campaigns with: choose a {{comm}} type from the drop-down for tagging your Mailchimp communications. The default is 'email'.
- If someone chooses to unsubscribe, who should Lamplight tell?: the drop-down list shows everyone who has access as a database operator. The unsubscribe notification will appear as a {{message}} in the diary and {{message}} list of whoever you choose.

Once you have finished, save your changes.


###### comms module


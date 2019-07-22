# 21.2.1    {{Comm}}s: Setting up Mailchimp in {{Lamplight}}

> You need to tell {{Lamplight}} about your MailChimp account so the two systems can talk to each other, through the system admin menu. 

xxxxx THIS IS JUST A PLACEHOLDER - NEEDS UP-TO-DATE INFO XXXXXX


Once you've set up your MailChimp account, you'll need you API key. This is similar to (but not the same as) a username and password that one computer program uses to identify itself to another. 

There are instructions to find your MailChimp API key [on the MailChimp site](http://kb.mailchimp.com/article/where-can-i-find-my-api-key): follow these to get the API key. 

You need to enter this into {{Lamplight}}: your system administrator will need to go to Admin -> system administration -> change global settings. On the {{Comm}}s module tab enter the API key. This is a long and unpleasant strings of characters and numbers that you'll want to copy and paste from MailChimp to {{Lamplight}}. Click 'save'.

![MailChimp API]({{imgpath}}225a.PNG)

Once you have saved your API key, go back into the global settings -> {{comm}} settings and complete the fields that tell Lamplight which {{workarea}} you want to assign to {{comm}}s, who you want to receive notifications of unsubscribes and which MailChimp list you want to use.

Within MailChimp you will create a single list as an umbrealla for all of your mailings. As {{Lamplight}} syncs with MailChimp it creates segments of that single list.

{{Lamplight}} will now be able to start talking to MailChimp to set up and send email newsletters. 

###### comms module


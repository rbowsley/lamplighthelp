# 21.2.2 {{Comm}}s Module: Creating MailChimp Mailing Lists in {{Lamplight}}

> You can use {{group}}s in {{Lamplight}} to set up mailing lists in MailChimp


You can sync existing {{Lamplight}} {{group}}s to Mailchimp. See section [12.0.0 Introduction to {{Group}}s](/help/index/p/12.0.0) for more on creating these. All of your {{Lamplight}} {{group}}s will connect to a single Mailchimp Audience, and will be identified within that, by the name of the Lamplight Group.

### To Sync {{Lamplight}} {{Group}}s to Mailchimp

- On the main {{Lamplight}} menu go to '{{group}}s -> view all'.
- Find the {{group}} which you want to link with Mailchimp and click on the context menu to the left of it (alternatively you can right-click on the {{group}} itself).
- From the context menu choose ‘View Mailchimp Status’.  
- You will see this message:

![Mailchimp New Sync Group Message](21.2.2a.png)

- Choose 'To sync with Mailchimp, click here'.
- You’ll see a rolling list of each subscriber as {{Lamplight}} syncs them with Mailchimp. You can close this or leave it open to see progress.
- You can also update a {{group}} which is already on Mailchimp from the same screen. You’ll see a description of the current status of the {{group}}, and the option: ‘To sync with Mailchimp, click here.’


### Viewing Your Audience Members in Mailchimp  

To view the profiles you've imported in Mailchimp, you can view your 'Mailchimp Audience'.  

- Log in to Mailchimp
- Choose ‘Audience’ from the main menu in the top left of the Mailchimp screen.  
- Scroll across the table to the 'Lamplight Sync Category' column - this shows the {{Lamplight}} {{group}} name and ID.
- Where a client is part of more than one {{group}} then this will be identified.

When you send a campaign through Mailchimp you will use these sync categories to identify the who to send to.

### Seeing a History in Lamplight of Mailchimp Syncs  

If you want to see all your {{Lamplight}} syncs with Mailchimp, go to 'admin -> system administration -> {{Comm}} Settings -> View Mailchimp event history'.

Each row in this table is a 'sync' of a list with Mailchimp.  To see details of what happened, click on the row of the table.  You will see each email address and the result from Mailchimp.

###### comms module


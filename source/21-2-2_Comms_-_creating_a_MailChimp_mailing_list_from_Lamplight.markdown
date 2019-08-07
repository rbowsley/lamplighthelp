# 21.2.2    {{Comm}}s - creating a MailChimp mailing list from {{Lamplight}}

> You can use {{group}}s in {{Lamplight}} to set up list 'segments' in MailChimp. Set up (or use an existing {{group}}) first, and then use the context menu to synchronise with MailChimp. 


xxxxx TODO XXXXXX


You'll need a {{group}} as the basis of your MailChimp list segment: see section [14.0.0  Introduction to {{group}}s](/help/index/v/{{version}}/p/14.0.0) for more on {{group}}s. When you are ready, go to {{group}}s -> view all on the main menu and find the {{group}} you want to use. When you open the context menu (right-click on the menu button), click on the 'View MailChimp status' option.

![{{Group}}s context menu - MailChimp options]({{imgpath}}240a.png)

If your {{group}} has never been used with MailChimp then there will be a single option, 'Start MailChimp sync now'. If you have used the {{group}} before you will need to click on 'Start MailChimp update now' to 

You also have the option to 'remove the link with MailChimp'. This will not delete your {{group}} from {{Lamplight}}.

When {{Lamplight}} starts to sync with MailChimp you will be able to see a 'Current sync status' summary box. As MailChimp imposes limits on how much information you can send it at once, the contacts from within {{Lamplight}} get sent to MailChimp in batches. You will see the numbers in the summary box changing as this is happening. When all of the rows, except the last one, are at 0 the sync with MailChimp has finished.

![Syncing with MailChimp]({{imgpath}}240b.png)

While this is happening you can create your newsletter in MailChimp by creating your own design or using one of their free templates.

###### comms module


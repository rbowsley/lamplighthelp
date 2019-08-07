# 21.2.0    {{Comm}}s - linking with MailChimp

> MailChimp is bulk mailing software that provides advanced reporting on your email communications. {{Lamplight}} can automatically link to and use MailChimp to send out email newsletters.

XXXXXXXXXXXXXXXXXX TODO XXXXXXXXXXXXXXXXXXXXX


MailChimp ([www.mailchimp.com](www.mailchimp.com)) is a powerful email marketing tool that lets you send bulk emails and report on the number that get successfully delivered, read, or forwarded. It can also manage subscriptions and unsubscriptions. This is a free service if you have fewer than 2,000 people on your mailing list and send under 12,000 emails in a month. 

To use MailChimp with {{Lamplight}} you need to have the {{Comm}}s module.

To get started you will need to create a free MailChimp account and then tell us you want to turn on MailChimp in your {{Lamplight}}.

You will need to enter a MailChimp API key into {{Lamplight}} to create the connection between the two.

As an overview, the link between the two systems works like this:

  1. You set up a {{group}} in {{Lamplight}} that you want to use as a mailing list in Mailchimp, and then ask {{Lamplight}} to tell MailChimp the email addresses it will need to send to.
  2. You compose your email in MailChimp, either by designing your newsletter or using one of the templates.
  3. You can view basic statistics about your newsletter in MailChimp.
  4. If anyone clicks on an 'unsubscribe' link in your email, MailChimp receives this notification and passes it on to {{Lamplight}}. {{Lamplight}} updates the 'send email' option on the profile of the person and removes their email address.

Please check the terms and conditions of MailChimp carefully, and in particular their guidance about [permission to send emails](http://http://mailchimp.com/legal/terms/). Please be certain that you have the permission (as described in the page linked to) for the email addresses you will be sending to. If you don't you may well get in trouble, and may get us in trouble too. We don't want that! 

###### comms module


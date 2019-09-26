# 21.2.0 {{Comm}}s Module: Linking with MailChimp Overview

> MailChimp is bulk mailing software that provides advanced reporting on your email communications. {{Lamplight}} can automatically link to and use MailChimp to send out emails and newsletters



MailChimp ([www.mailchimp.com](http://www.mailchimp.com)) is a powerful email marketing tool that lets you send bulk emails and report on the number that are successfully delivered, read, or forwarded. It can also manage subscriptions and unsubscriptions. This is a free service if you have fewer than 2,000 people on your mailing list and send under 12,000 emails in a month. 

To use MailChimp with {{Lamplight}} you need to have the {{Comm}}s Module.

To get started you will need to create a free MailChimp account and then tell us you want to turn on MailChimp in your {{Lamplight}}.  You will then need to enter a [MailChimp API key into {{Lamplight}}](/help/index/p/21.2.1) to create the connection between the two.

As an overview, the link between the two systems works like this:

  - You set up a {{group}} in {{Lamplight}} that you want to use as a mailing list in Mailchimp, and then ask {{Lamplight}} to tell MailChimp the email addresses it will need to send to.
  - You compose your email in MailChimp, either by designing your newsletter or using one of the templates.
  - Mailchimp sends your email to the chosen mailing list.
  - A copy of the email is sent to {{Lamplight}} and stored as a {{comm}} record
  - You can view basic statistics about your newsletter in MailChimp.
  - If anyone clicks on an 'unsubscribe' link in your email, MailChimp receives this notification and passes it on to {{Lamplight}}. {{Lamplight}} updates the 'bulk email' option in the contact details of the profile of the person.

Please check the terms and conditions of MailChimp carefully, and in particular their guidance about [permission to send emails](http://mailchimp.com/legal/terms/). You need to be certain that you have permission to send to the email addresses in your lists: if you don't you may well get into trouble under GDPR legislation, and may get us in trouble too. We don't want that! 


###### comms module


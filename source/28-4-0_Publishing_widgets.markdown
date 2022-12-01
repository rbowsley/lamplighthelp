# 28.4.0 Publishing widgets

> Publishing module widgets allow you to display published records from Lamplight on your own website just by copying a single line of html to your website.


Publishing widgets are html iframe elements that display the published records from your system on your own website. You
don't need a software developer to do this: you create the widget in Lamplight system admin, and then copy and paste the
html code to your own website.

To do this you'll need to be able to edit the html of your website. Most website platforms like Wordpress allow you to
do this, but if someone else controls your website you may need to ask them to insert the widget: but it really is just
a case of pasting a single line of html Lamplight generates.

### Video walkthroughs

We've created three videos that show you how to set up widgets and add them to a website. We work through each 
step to create three different types of widget. Watch them [in the hub](/help/index/p/52.5).

### Types of widget

You can create widgets that

- list published profiles
- create new profiles
- create a new {{referral}} record
- create a new profile and a {{referral}} attended by that profile
- list published {{work}} records
- list published {{work}} records and allow people to add themselves to it as attendees.

You can create as many widgets of each type if you need to. For example, you may have one widget that lists your staff
members, and another directory listing that shows other partner organisations who may be of interest to your web
visitors.

Widgets can also include your own styles if needed - if you want to change the colour, font, or other layout elements,
for example. You'll need to include CSS statements to do this. You may be able to copy these from your main website, but
if not you may need some help from a web developer. But the default styles are designed to be clean, attractive, but
fairly neutral, and should be enough for many uses.

Creating widgets does not alter the overall security settings for the publishing module. For example, you will need to
make sure that you've turned on 'allow publish {{work}} records' if you want to use a {{work}} record listing
widget.  [Section 28.2](/help/index/p/28.2) explains how to change overall publishing settings.

### Creating and managing widgets

To see and add widgets go to admin > system admin > Publishing module > Manage publishing widgets that show published
data on your website. You'll see any widgets you already have, and buttons to create new ones.

![System administration - publishing widgets](28.4.0a.PNG)

Click the 'edit' or 'delete' buttons to change an existing widget. Note that if you do make a change, it will take
effect straight away. If you're already using a widget on your website, it will be changed, and if you delete it, it
will stop working immediately.

When you're ready to use a widget, copy the html code in the grey box and paste it into your website in the right place.

If you want to test a widget before including it in your website, you can copy the URL from the iframe (in the grey box,
starting https://lamplight.online/...), and view it in a browser - but not the one you're logged into Lamplight with (
use a different browser or an incognito/private window).

#### Profile list widgets

To create a new Profile Listing widget, click the 'list profiles' button at the top of the admin screen. You'll see a
popup window like this:

![System administration - creating a profile listing widget](28.4.0b.PNG)

The publishing feed name is just for your reference and is only shown in the system admin section. CSS statements can be
entered if needed. You need to choose a profile role and type, and you can only choose one of each. Save the widget, and
you'll see the listing of all widgets and the html code you need.

Without any custom CSS, the profile listing will look like this:

![Profile listing widget](28.4.0c.PNG)

The image is from [www.gravatar.com](https://www.gravatar.com) - a public system that allows you to associate an image
with your email address. If the email address has a gravatar image associated with it, it will be displayed. The search
box in the top-right corner will search the published data for profiles.

#### Add profile widget

The Add Profile widget creates a new profile in your system. Click the 'create profiles' button and you'll see a popup
window.

You'll need to give it a name and set any styles you want, and then tell it what type of profile the widget should
create. Remember you can create lots of widgets if you need to be able to add different profile types. You'll then see
space for text to appear around the form elements, which include some default text to help you get started but which you
will need to update from your own data protection/privacy policy. There's also space to link directly to your privacy
policy.

Finally, you can select any custom fields you want to be included in the form. Only fields that are set to allow changes
via the API are listed here: you'll need to go to [manage custom fields in profiles](/help/index/p/16.7.0) if the fields
you need are missing here. Each field is listed showing the profile types that it appears on - you must make sure that
you choose fields that match the profile type you selected earlier.

You can also drag and drop the fields into a different order if you need to.

An example Add Profile widget with custom fields and some customised text looks like this:

![Add Profile widget](28.4.0i.png)

When you save a widget, the form is saved as it is, with the custom fields as they currently are. If you now go and add
some options to a custom field, the Add Profile widget **will not** update automatically. You will need to edit your
widget and save it for it to update with the new options.

These widgets are designed to be mobile friendly: if you view on a smaller screen the form fields switch to one per
'row':

![Add Profile widget on a smaller screen](28.4.0j.png)

#### Accept {{referral}} widget

To create a widget that will allow people to create {{referral}} records from your website, click the 'accept
{{referral}}' button at the top. Set the name of the widget and any custom styles. You can also choose a default
{{workarea}}, whether to allow text for the {{referral}} reason, and include custom {{referral}} fields.

If you don't select a {{workarea}}, a drop-down will be shown on the public form to allow the end user to select one.
Most of the time we'd suggest you set a {{workarea}} here, and edit it within {{Lamplight}} if needed after it's been
received.

Note that this widget does not create a profile automatically. The {{referral}} record that's created will try and match
the profile by email address, and include the text from the 'details' in the '{{referral}} reason'.

![Publishing - creating an accept {{referral}} widget](28.4.0d.PNG)

Without any custom CSS, an Accept {{Referral}} widget (without custom fields and with a {{workarea}} select) will look
like this, and the referral topic select box lists your {{workarea}}s:

![Accept {{referral}} widget](28.4.0e.PNG)

Without any custom CSS, an Accept {{Referral}} widget with a custom field and no {{workarea}} will look like this:

![Accept {{referral}} widget with a custom field](28.4.0h.png)

When you save a widget, the form is saved as it is, with the {{workarea}}s and custom fields as they currently are. If
you now go and add some options to a custom field, the Accept {{Referral}} widget **will not** update automatically. You
will need to edit your widget and save it for it to update with the new options.

#### Profile and {{referral}} widget

A Profile and {{Referral}} widget will create a profile and a {{referral}}, with the profile added to the {{referral}}
record. It's a combination of the 'Accept {{referral}}' widget and the 'Add profile' widget in one.

To create one, click the 'profile and {{referral}}' button. The form for the widget now includes all the settings for
the profile *and* the {{referral}}: see the other sections of this page for more details about these.

#### {{Work}} record listing widget

To create a widget that will show a list of published {{work}} records click the '{{work}} record listing' button at the
top.

![Publishing - creating a {{work}} record listing widget](28.4.0f.PNG)

You can optionally add a filter for {{workarea}} and location here, to only show records for one or more {{workarea}}s.
If you want to show all, leave these unticked.

Without any custom CSS, the {{work}} record listing widget will look like this:

![{{Work}} record listing widget](28.4.0g.PNG)

The 'Title of record for publishing' from the {{work}} record is the main title, with date, time and {{workarea}}
displayed below.


#### Attend {{work}} widget

And Attend {{Work}} widget is similar to a {{Work}} Record Listing widget, but also allows people to add themselves as 
attendees on the record.

Create the record by clicking the 'attend {{work}}' button and add any filters to limit the records displayed.  Note that
only {{work}} records that are published will be shown anyway.  You can also limit the list to records that have 
'allow people to be added via the API' selected in the {{work}} record.

The widget will look a bit like this:

![Attend {{work}} widget](28.4.0k.png)

Each record has a 'tick to register' box, and then at the foot of the page a space for their email address.  When you
complete this {{Lamplight}} will try and find a profile with this email and add them to the {{work}} records selected.
If it can't find a profile, or finds more than one, it will create a {{message}} within the system letting you know.


###### publish module


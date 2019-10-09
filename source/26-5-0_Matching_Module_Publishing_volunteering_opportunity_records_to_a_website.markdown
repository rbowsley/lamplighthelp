# 26.5.0 Matching Module - Publishing {{volunteering opportunity}} records to a website

> Create 'API feeds' - an easy way to embed a searchable list of {{volunteering opportunity}} records on your website or elsewhere

The Matching Module includes the ability to publish {{volunteering opportunity}} records externally.  This is separate to the publishing module, and does not require it to work.  The easiest way to do this is to create 'feeds' - embeddable widgets that you can copy and paste into your website quickly and easily.  You set up these feeds with a few starting criteria within {{Lamplight}} as a system administrator.

Only {{volunteering opportunity}} records that you publish when you create them ([see section 26.2.1](/help/index/p/26.2.1)) will appear in API feeds.

### Create a new feed

Go to admin > system  administration and in the 'Matching Module' section click 'create new API feed'.  You will see any feeds you have already set up, and below that a form to create a new one:

![Create new {{volunteering opportunity}} feed](26.5.0a.PNG)

#### Feed name
This is just for your reference. You can create multiple feeds for different purposes (perhaps a small 'near us' widget on a home page, and a full search form on a separate page).  Give your feed a name that will remind you where you've used it later.

#### Include a search form?
A simple search form can be embedded in the feed, so that people using your site can narrow down the results they see.

#### Postcode to centre requests around
Use the geocoded addresses of the {{opportunity provider}} (or the {{volunteering opportunity}} to only show records centred on the postcode you provide here. You also need to specify a maximum distance from this point for this to take effect.

#### CSS files to include in the header
What you get from an API feed is well-structured html with no styling, so that it can take on the styles of your own site. See [section 26.5.1](/help/index/p/26.5.1) for more technical details about the structure of the response you'll get.

Any CSS files you specify here will be included in the head element of the embedded iframe, so you can reference the CSS of your main site if you want to.


Click 'save' when you are done and you will see something like this:

![Created {{volunteering opportunity}} feed](26.5.0b.PNG)

Copy and paste the html (the bit in the box starting &lt;iframe) to your own website and you should see {{volunteering opportunity}} records immediately.



###### match module

# 24.1.0    Publishing module security

> The publishing module has multiple safeguards built in so that only the data you want to publish is accessible. 

The publishing module works by creating web addresses that your website can request. {{Lamplight}} will respond to these requests with the relevant data: your web server can than process this information to display it within your site, in the style that you want it.

However, for these requests to be successful, the following checks all have to pass:

  1. Is the publishing module turned on?
  2. Does the request have the correct credentials (equivalent to a username and password)?
  3. Is the type of information requested (e.g. {{work}} records or {{people}}) allowed to be published?
  4. Is the particular record being requested published (e.g. {{work}} record number 123)

If all those checks pass successfully, {{Lamplight}} will then check which pieces of data can be published (e.g. name and phone number but not email address) and send it to your web server. And of course, your data is still in your control, so you could add additional controls on your web server (e.g. don't display {{work}} records that have a particular {{workarea}}, or add a registration/signin mechanism to restrict information to your members). This approach gives you a very fine level of control about what data is published, and where to. 

###### publish module


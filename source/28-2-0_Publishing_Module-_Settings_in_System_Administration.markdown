# 28.2.0 Publishing Module: Settings in System Administration

> To be able to share information between Lamplight and your public-facing web or social media site you will first need to set permission levels in system administration



Your System Administrator can set the details of information that may be transferred from {{Lamplight}} to the public-facing site that has been granted permission to receive it. This needs to happen before anything can be published from {{Lamplight}}.

**Please note: These settings do not directly publish information, but simply set permissions for what information can be published.**

- Go to 'admin -> system administration' and in the 'Module Administration' section towards the bottom you will find the 'Publishing Module' box.
- Click 'Manage publishing settings'. 
- In this page are several tabs controlling how publishing works within the system. 

### Overall Publishing Details  

The options in this tab control the type of information can be published and updated from an external site. Simply select the options you want. You will then need to go to the specific tabs to set the detail of what can be published.

![Publishing Settings](28.2.0a.png)

You can choose whether to:
- Publish details of {{people}} or {{org}}s.
- Allow profiles to be created.
- Allow existing profiles to be updated.
- Publish details from {{work}} records.  

### {{People}} and {{Org}}s Tabs  

These tabs are where you set the detail of information you will be able to share from profiles.

![Details of Profile That Can Be Published](28.2.0b.png)

- The options in the ‘{{People}}’ tab relate to any profile which was added under ‘{{People}} > add {{person}}’ in the main menu. 
- The options in the '{{Org}}' tab relate to profiles which were added as {{org}}s. 
- If you have '{{Family}}' activated as a role, there will also be a ‘{{Family}}’ tab. 
- In these tabs you can choose:
   - which roles can be published.
   - what profile details can be published.
   - what profile information can be added to Lamplight from a website/application.
   - what profile information can be updated within Lamplight from a website/application.

### {{Work}} and {{Referral}} Tabs  

You can use these tabs to identify exactly which parts of the {{work}} or {{referral}} records can be published, and which information can be added to these records from an external site. 

![Details of {{Work}} Records That Can Be Published](28.2.0c.png)

Once these permissions are set each {{work}} or {{referral}} record will also need to be published manually as you create or edit it.

### {{Project}}s

If you have multiple Lamplight {{project}}s you can choose which ones will allow publishing.

### API Key and Details  

The API key and details tab are the credentials your website will need to access data in {{Lamplight}} - think of this as a username and password that your website needs in order to get information from {{Lamplight}}. 

- This section gives you the API key you will need to access Lamplight remotely. Give these details to your programmer.
- To generate a new API key, click the checkbox and choose ‘save’. Previous keys will no longer function, and you’ll need to update your applications and programming.

### Additional Profile Data  

‘Managing publishing settings’ in system administration allows you to decide what standard profile data to share to an external website. You can also publish custom profile data (unique to your system’s set-up). 

To do this:
- In system admin, find the custom field that you want to share (for more on this see [16.7.2 Adding and Editing Custom Tabs and Fields in Profiles](help/index/p/16.7.2), and [16.7.4 Adding and Editing Custom Tabs and Fields to {{Work}} and Other Records](/help/index/p/16.7.4)).
- Open it to edit, and tick the 'Should the data in this field be published?' option.
- Click 'save'. 


###### publish module


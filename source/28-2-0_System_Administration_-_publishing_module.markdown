# 28.2.0 Publishing Module: Settings in System Administration

> As system administrator you have the authority and responsibility to set the permission levels for the types and details of information that may be transferred from {{Lamplight}} to the public facing site that has been granted permission to receive it. 

You will need to configure these settings to determine what can be published from Lamplight.

### Publishing Settings

- Go to the system administration section within the admin settings
- Under 'Manage Publishing', click 'manage publishing settings'. 
-In this page are several tabs controlling how publishing works within the system. None of these tabs publishes information, but simply sets permissions for what information can be published.

![publisting settings](215a.png)

- Tick or untick the boxes according to the information you wish to allow your system to publish, and whether you want it to be possible to add new profile information through the website. 

**Overall Publishing Details**
   
- This controls what sort of information can be published and updated from an external site. Simply select the options you want.

**{{People}} and {{Org}}s Tabs**
  
- ‘{{People}}’ refers to any profile in Lamplight which is added under ‘{{People}} > add {{person}}’ in the main menu. 
- The {{Org}} tab identifies profiles which were added as {{org}}s. If you have '{{families}}' activated as a role, there will also be a ‘{{Families}}’ tab. The options here relate to:
   - which roles can be published
   - what details to publish
   - what information can be added to Lamplight from a website/application
   - what information can be updated within Lamplight from a website/application

**{{Work}} and {{Referral}} Tabs**

You can use these tabs to identify exactly which parts of the work or referral records can be published, and which information can be added to these records from an external site. This is just the permission for parts of records to be published, but each work or referral record will also need to be published manually as you create or edit it.

**{{Projects}}**

If you have multiple Lamplight {{projects}}, this identifies which ones will allow publishing.

**API Key and Details**

The API key and details tab are the credentials your website will need to access data in {{Lamplight}} - think of this as a username and password that your website needs in order to get information from {{Lamplight}}. This section gives you the API key you will need to access Lamplight remotely. Give these details to your programmer.

To generate a new API key, click the checkbox here and choose ‘save’. This will generate a new key, and previous keys will no longer function. You’ll need to update your applications and programming once you’ve done this.

**Additional Profile Data**

‘Managing publishing settings’ in system administration allows you to decide what main profile data to share to an external website. You can however also publish custom profile data (unique to your system’s set-up). 

To do this you will need to alter settings to identify which fields should be published by editing each one separately. For more on this  see section [18.3.0  System Administration - Custom profile tabs and fields for {{people}}](/help/index/p/18.3.0).


###### publish module


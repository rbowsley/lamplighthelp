# 16.12.2 Global Settings: Data to Store

> The 'Data to store' tab contains options relating to the types of records you want to create and what information you would like to include. 

See below for explanations of the different fields:

**Do you want to use {{message}}s at all?
{{Message}}s are an optional function in Lamplight. They are not used in reports, but can be a useful way of keeping track of things that need to be accomplished.

{{Message}}s are associated with a date and time, assigned a category and/or flag (these are specified in admin>system administration>Manage drop-down lists>{{Message}}s), and can be marked as complete, along with a date and time, when accomplished.

{{Message}}s are also linked to profiles and can be viewed directly in a profile’s ‘{{Message}}’ tab, which is enabled if this option is selected.

{{Message}}s appear in a table, such as the one below. As this {{message}} has been associated with a database operator, it is showing up in the ‘{{Message}}s’ tab on their homepage.
 
xxxxxx Picture herexxxxxx

{{Message}}s can also be added to {{work}} records and {{referral}} records in the ‘{{Message}}’ tab. {{Message}}s created in records can still be viewed in profiles associated with them.

xxxxxx Picture here xxxxxx
 
**Do you want to allow bulk updating of the attendance table in {{work}} and other records?**
When adding profiles to the attendance table in a {{work}} record, {{referral}} record or {{outcome}} record, you must usually specify attendance type and role for each profile, as well as adding any notes.

With this option enabled, there is an additional row in the table that allows you to edit these fields for all profiles added to the attendance table at once.

xxxxx Picture here xxxxxx

**Do you want to allow adding new service user profiles from {{work}}, {{referral}} etc. records, even if you have profile essential fields enabled (see previous tab)?**
If you have specified essential fields for adding profiles, it is not usually possible to create new profiles from within a {{work}}, {{referral}} or {{outcome}} record. This is because profiles created in this way will not have the essential fields completed upon creation.

Enabling this option will mean that profiles can be created in this way despite lacking the essential information specified in global settings.

If you want to use this option, it is important to remember that such profiles will need updating following their creation.


### {{work}} records

**Do you want to store{{work}} records?**
{{work}} records are enabled by default in Lamplight. They allow users to record {{work}} they have done and can be used in many ways, including producing detailed reports. For most Lamplight users, they represent key element of their system.

If you do not use Lamplight to record your {{work}}, for example if you only use your system to track contact information, you can disable {{work}}records entirely using this option.

**What is the default length of one {{work}} record (minutes)?**
When entering {{work}} records in Lamplight, there is a default duration of sixty minutes. What this means is that, when you specify a start time for a {{work}} record, the end time is automatically set to sixty minutes later. This reduces the amount of {{work}} that you do to enter records if you usually record sixty-minute periods of {{work}}.

If you usually see clients for a set amount of time that it not sixty minutes, changing this setting will reduce the amount of data entry you need to do for each{{work}} record.

For example, if a typical appointment within your organisation lasts thirty minutes, it would make sense to change this setting to thirty.

Note that it remains possible to adjust each {{work}} record, this setting is simply a quality-of-life improvement that could reduce how many clicks it takes to enter repetitive information.

**Do you want to use {{message}}s with {{work}} records?**
If you have enabled {{message}}s in your system, there will be a ‘{{message}}s’ tab on {{work}} records which allows you to link {{message}}s to them. You can disable this option to hide this ‘{{message}}s’ tab and keep {{message}}s separate from {{work}} records.

**How many years back should the dates go in {{work}} records?**
When creating or editing a {{work}} record, the year is selected using a drop-down menu. By default, this list goes back ten years, which is enough for most purposes. 
 
xxxxxx picture here xxxxxx 
 
If you need to enter historical records onto your system, you can adjust this setting so that this list goes back further than ten years, allowing you to enter records from further back in time.

**Do you want to add a "add to diary" tickbox on {{work}} records?**
By default, when a {{work}} record is created it is added to the diaries on the home page. This includes both the ‘My Diary’ tab and the shared ‘Diary’ tab.

This option allows you to choose whether to add {{work}} records to these diaries by adding a tickbox at the bottom of the ‘When and where’ tab on {{work}} records as shown here.
 
xxxxxx Picture here xxxxxx 
 
Note that if you enable this, operators will be able to create {{work}} records that do not show on the home page diary, but these records remain accessible to all operators as normal (for example in {{work}} > view > {{work}}) so this feature does not restrict access to information.

**Do you want plain text or rich text boxes for summary, description and follow up?**
When entering summary, description and follow-up information in {{work}} records, by default the text boxes are ‘rich text boxes’, which means that they offer options for formatting, including different typeface, different font sizes, bold, italic and underlined type, etc. as in the example below.

xxxxxx Picture here xxxxxx

If you don’t require these formatting options, this option changes these to plain text boxes instead, as in the example below.

xxxxxx Picture here xxxxxx


### {{Outcome}} records

**Do you want to store {{outcome}} records?**
{{Outcome}}s in Lamplight are used to track change over time. An {{outcome}} record functions as a snapshot from one point in time, and multiple {{outcome}} records can be compared to measure the difference. They are primarily used to understand the difference an organisation’s work is making, and are very useful for presenting this information numerically for reports or funding proposals. By default, {{outcome}} records are enabled.

xxxxxx Picture here xxxxxx

{{Outcome}} records can be viewed or created in the main menu through {{work}}>view>{{outcome}} and {{work}}>add new>{{outcome}}, respectively. An individual’s {{outcome}} records can also be viewed and created through the ‘{{outcome}}s’ tab in their profile. This functionality can be disabled for simplicity if {{outcome}}s are not needed in your system.

**Do you want to use {{message}}s with {{outcome}} records?**
With this option, {{message}}s can be associated with {{outcome}} records in the same way that they can be associated with {{work}} records and {{referral}} records. A {{message}}s tab becomes available when adding a new {{outcome}} record through the main menu, as shown here:
 
xxxxxx Picture here xxxxxx

**Do you want to use simple or tabular attendance information on {{outcome}} records?**
By default, profiles added as attendees on an {{outcome}} record are listed in a table. This allows for multiple {{people}} to be added in different roles, as in the example below.

xxxxxx Picture here xxxxxx

If this functionality is not required, and the most that will be listed on an {{outcome}} record is one service user profile and one staff profile, the simple search box may be sufficient. It appears as in the example below. An important thing to remember when using this simple view is that you must select the profile from the search options that appear as you type, rather than just typing the name. This will ensure that it is linked to the correct profile.
 
xxxxxx Picture here  xxxxxx

**Tick the "our {{work}}" checkboxes by default**
These checkboxes are used to indicate whether an {{outcome}} change has been as a result of your work. They are ticked by default unless you deselect this option. 

xxxxxx Picture here xxxxxx


### {{Referral}} records

**Do you want to store {{referral}} details?**
{{Referral}} records are one of the core types of information that can be recorded in Lamplight. In their simplest form, they track who has been referred, who has referred them and who they have been referred to, along with {{referral}} reason, additional notes and details of the date, time and relevant {{work}} area. They can also be configured to record different ways in which one {{person}} is directed to another contact or service, for example signposting. If you do not require this type of information to be recorded in Lamplight, you can disable the functionality with this option.

**Do you want to use {{message}}s with {{referral}} records?**
Just as you can associate {{message}}s with {{work}} records or {{outcome}} records, you can choose to associate them with {{referral}} records. This option is enabled by default but can be turned off if you do not require it.

**Do you want to use simple or tabular attendance information on {{referral}} records?**
As with respondents in {{outcome}} records, profiles can be added to {{referral}} records using either the default table style or simple search boxes. In the simple search box view on {{referral}} records, there are three fields: referrer, service user referred and who they were referred to, as shown below.

xxxxxx Picture here xxxxxx
 
**Show date to when adding {{referral}} records?**
For most purposes it may be enough to record the time and date of {{referral}}, in which case you will not require this option. To record a duration for {{referral}}s, you can enable this to allow the entry of a second time and date field, as shown below.

xxxxxx Picture here xxxxxx
 

### Grant records

**Do you want to store grant details?**
Lamplight can be used to record details of grants. As well as time and date, {{workarea}} and attendance information (which are common across all types of record), grant records can contain information about whether a grant is for capital or revenue, with an approval date, grant amount, and text fields for summary, description and monitoring requirements. If you don’t use Lamplight for recording grant information, disabling this option will prevent the extra menu options from appearing.

**Do you want to use {{message}}s with grant records?**
As with {{work}} records, {{outcome}} records and {{referral}} records, you can choose whether to enable {{message}}s with grant records. Disabling this option will prevent the ‘{{Message}}s’ tab from appearing when entering grant records.


### {{Evaluation}} records
**Do you want to use {{message}}s with {{evaluation}} records?**
As with {{work}} records, {{outcome}} records, {{referral}} records and grant records, you can choose whether to enable {{message}}s with {{evaluation}} records. Disabling this option will prevent the ‘{{Message}}s’ tab from appearing when entering {{evaluation}} records.

**Do you want to use simple or tabular attendance information on {{evaluation}} records?**
As with respondents in {{outcome}} and {{referral}} records, profiles can be added to {{evaluation}} records using either the default table style or simple search boxes. In the simple search box view on {{evaluation}} records, there is one field for ‘Who completed the {{evaluation}}’, as shown below.

xxxxxx Picture here xxxxxx

**Show date to when adding {{evaluation}} records?**
As with {{referral}} records, you can choose to specify a ‘date to’ as well as a ‘date from’ for {{evaluation}} records, allowing you to show a duration rather than a single point in time.


###### core system

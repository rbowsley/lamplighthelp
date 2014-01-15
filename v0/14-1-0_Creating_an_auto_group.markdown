# 14.1.0    Creating an {{auto group}}

> On the main menu go to {{Group}}s -> Add -> Add {{auto group}}. Give the {{group}} a name and description; enter your search criteria, and click 'Save'. 

On the main menu go to {{Group}}s -> Add -> Add {{auto group}} and you will see the following screen:

![Creating an {{auto group}}]({{imgpath}}103a.png)

This screen allows you to go to the tabs relevant for your {{group}} in order to specify your criteria. {{Lamplight}} will include people/organisations that meet ALL the criteria you enter. Note too that all numeric and date comparisons in {{Lamplight}} are inclusive (for example >=, not > ).

When you have added all criteria, click the 'save' button in the bottom-right.

**{{Group}} name tab**: the name and description of the {{group}} are to help you and other users of the system remember what this {{group}} is for. Both are required fields. There is also a tick box to allow you to 'lock' the group. This means that only you will be able to edit the {{group}} once it has been created.

**{{People}} or organisations tab:** do you want a {{group}} of individuals, or organisations? What types of {{people}} do you want?

![{{Auto group}}s - choosing what types of {{people}} to add]({{imgpath}}103b.png)

You cannot create a {{group}} of both {{people}}. The search for the type of {{person}} ({{user}}, {{staff}}) etc. is an 'OR' search: it will include those that meet any of the criteria selected, not just those that meet all of them. The date option at the bottom of this page allows you to select the timeframe profiles were added to the system. Greater than or equal to 1st January 2014, would give you a list of all those added since the beginning of 2014.

**Address:** search by address. You can search particular lines of the address, or more reliably search any part of it, or by postcode. When searching by postcode, you can enter multiple postcodes (or partial postcodes) separated by a semi-colon (;). Whenever you search for text, you can select how the search should be carried out: 

  * Exact match - the phrases should be identical, but case-insensitive (so 'hello' matches 'HeLLo')
  * Match anywhere - will match the entire string wherever it occurs (so 'stone lane' matches '15 Stone Lane', and matches '15 Brightstone Lane', but does not match '15 Stonecroft Lane'.
  * Starts like - will match any strings that start with the search string

Spaces at the beginning and end of address lines is excluded from searches.

  * Ward and Borough - lists (if you use the Ordnance Survey look-up and Geo-code) will be populated based on the address details within the contact details page of the profiles in the system. You can select more than one from this list. Use the Ctrl button on your keyboard, if you want a list of people or organisations from Kensington and Chelsea and Kirklees (for example). 

**Relationship:** searches by relationship created between {{people}}. This allows you to create {{group}}s of, say, 'parents' or 'trustees'. You also have the opportunity to use a second relationship. For example you may have parents and children linked together by a relationship. Parents have a custom field in their profile about 'employment status' for example. You can create a list of children whose parents are unemployed. So you would initially create your {{auto group}} of unemployed parents and then create a second {{group}} of children who are related to your 'unemployed parents' {{auto group}} from the drop-down list.

**{{User}} fields, {{staff}} fields, {{funder}} fields etc:** are fields set up for {{user}}s, {{staff}}, and {{funder}}s respectively, so the choices will depend on how your system has been set up (and may not be visible at all if there are no fields set up).

The comparisons vary depending on the type of field. Date and number fields may be matched as either: 

  * Greater than or equal to, meaning that people with a value greater (or later) than or equal to the value you specify will be included.
  * Less than or equal to
  * Equal to

Where there are multi-select options, only those that match all of your selections will be included in the {{group}}.

**{{Work}}** fields lets you filter for {{people}} based on {{work}} records. If you want to find {{people}} that have attended based on dates, you first need to set the dates, you need to specify what {{work}} has happened around those dates. You can also specify if you want to be sure that you find people that have not attended at certain periods. So, for example:

To identify people attending at least one session of Cookery after 1st April 2012 and before 31st March 2013:

![Automatic groups - {{work}} records tab example 1]({{imgpath}}103c.png)

To identify people attending an Initial Assessment between 1st April 2012 and 30th September 2012 (equivalent to people attending between Start of Q1 2012 and End of Q2 2012)

![Automatic groups - {{work}} records tab example 2]({{imgpath}}103d.png)

To identify new users - people attending the centre after 1st April 2013 that had never attended before then:

![Automatic groups - {{work}} records tab example 3]({{imgpath}}103e.png)

To identify attendees who have completed the course - service users who in Q3 2013 attended at least 6 sessions of the 10 session Gardening course

![Automatic groups - {{work}} records tab example 4]({{imgpath}}103f.png)

Finally, you can add filters by {{workarea}}, attendance type and role, and any custom {{work}} fields you have added to your system.

The **{{Outcome}}** fields tab lets you search for {{people}} based on their outcome scores of a particular measure. You can choose to for {{people}} with a particular scores, change over time or those who have maintained a score for a specified period of time. This will let you set up {{group}}s like '{{people}} that have gained a job and have sustained it for 6 months'. Bear in mind here that {{Lamplight}} treats yes-no {{outcome}}s as 1 - 0 (ie a 'yes' is stored as 1, and a 'no' as a 0, so to find {{people}} that have answered 'yes' to a particular {{outcome}} you'll need to enter 'Outcome score' as 'Equal to' '1'. 

**{{Referral}}** fields and **{{Grant}}** fields operate in a similar fashion to the {{work}} fields tab. However within these field tabs you are searching for {{people}} involved in a {{referral}} or {{grant}} records respectively. 

**{{Cases}}** tab allows you to create a list of {{people}} who are involved in a particular case by name, category or within a timeframe.

[View the video](/help/video/id/18)
###### core module


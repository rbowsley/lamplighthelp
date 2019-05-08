# 11.1.0    Creating an {{Auto Group}}

> An auto {{Group}} allows you to add selection criteria which {{Lamplight}} then uses to match profiles to the group. They can be set up either for {{people}} or {{org}}s


With {{groups}} in {{Lamplight}}, less is often more. It is important to know what it is that you are looking for before you start, and not to add too many filters to your group as you could exclude all possible members in this way. The only two tabs that you have to fill out are the 'Group name' and '{{People}} and {{org}}s ones. You should pick the filters you need carefully from the other tabs. Once you have finished choosing filters, your {{group}} will include {{people}} or organisations that meet **ALL** the criteria you have entered. 

To set up a new {{group}}, On the main menu go to '{{group}}s -> add -> add {{auto group}}'. You will see the following screen:

![Creating an {{auto group}}](103a.png)

### {{Group}} Name

The {{group}} a name and a description and compulsory - you can't save your choices without filling these in.  
 - Choose something that makes it clear who your {{group}} is made up of as these fields are used to remind you and other users of what the {{group}} is for - you will not be the only person using it. 
- If you use this group for a specific purpose, such as quarterly reporting of for a particular funder, you can make a note of this in the '{{Group}} description' field to make it easier to find the next time you need it, and also alert others to its purpose. 
- There is a 'Lock {{group}} option here.  If you tick this box then only you will be able to edit the {{group}}. If it is important that you know the criteria stay the same, for example when creating a regular {{group}} for reporting, then we would recommend you choose this option. 


### {{People}} or {{Org}}s
 
![{{Auto group}}s - choosing what types of {{people}} to add](103b.png)

- You must choose whether your auto {{group}} will include {{people}}, {{org}}s or {{families}} - you cannot have a mixture. If you need more than one of these types, you can create a {{group}} for each and them merge them (see [11.3.0 Creating a Merge {{Group}}](/help/index/p/11.3.0) for more details). 
- Unlike most fields in auto {{groups}}, 'who are' choice (e.g. {{user}}, {{staff}},{{contact}} etc.) is an 'OR' search, so it will include those that meet **any** of the criteria selected, not those that meet all of them. 
- Next is the option to select the date profiles were added to the system.
  - Greater than or equal to means on this date or after it. So greater than or equal to 1st January 2019 would give you everyone profile which had been added to the system on or after 1st January 2019.
  - Less than or equal to means on this date or before it. So again, if you  put in 1st January 2019, you would see all profiles added on or before 1st January 2019.
  - Equal to means on that date. As with previous examples, using 1st January 2019 would only show you people added that day.
  - Between. If you choose this option, a second date box will appear so that you can specify two dates. For example, if you want to see all the profiles added in 2018, you would specify between 1st Jaunary 2018 and 31st December 2018. The dates in this filter are inclusive (so records falling on that day will be added to the {{Group}}.
- The 'visibility' drop-down box allows you to choose whether your group will be made up of people who are active on your system, or those who have been archived. For more on archiving, see [16.8.2 Archiving Profiles](/help/index/p/16.8.2). You cannot mix current and archived profiles in the same auto {{group}}.


### Address

In this tab you can search by particular lines of the address, any individual part of it, or by postcode. 
- When searching by postcode, you can enter multiple postcodes (or partial postcodes) separated by a semi-colon (;). 
- Whenever you search for text, you can select how the search should be carried out: 
  - Exact match - the phrases must be identical, but it is not case sensitive (so 'hello' matches 'HeLLo').
  - Match anywhere - will match the entire string wherever it occurs (so 'stone lane' matches '15 Stone Lane', and matches '15 Brightstone Lane', but does not match '15 Stonecroft Lane').
  - Starts like - will match any strings that start with the search string (so 'Brighton' will match 'Brighton Villas' but not 'New Brighton').
  - Is empty. If you want to find all profiles that do not have any information in the field (for example postcode) then choose this option.
- Spaces at the beginning and end of address lines are excluded from searches.
- Ward and Borough (if you use the Ordnance Survey look-up and Geo-code): these will be populated based on the address details in the contact tab of each profile. You can select more than one ward or borough from each list. To do this, hold down the Ctrl button on your keyboard while you click on the options that you want, e.g. Chichester and Chiltern. To deselect an option, Ctrl click again.

### Relationship

On this tab you can choose to filter by the relationships that are recorded in the profile.
- This allows you to create {{group}}s of, say, all the {{people}} who have a relationships of 'key worker', 'GP' or 'trustee'. 
- You can also use relationships to another {{group}}. For example, you may have one already set up  for people who are unemployed. To  create another {{group}} of the family members of these people who are unemployed, choose the original 'unemployed' {{group}} from the 'show only people that are related to members of group:' dropdown, and the relationship 'family' from the 'With relationship' box.

![Using Relationship Links in a {{Group}}](/help/index/p/11.1.0a.png)

### {{User}} Fields, {{Staff}} Fields, {{Funder}} Fields etc

These tabs contain all the custom fields that you have in the profiles of your {{user}}s, {{staff}}, and {{funder}}s respectively.  
- The choices here will depend on what is in your individual system, but may include such things as demographic information.  
- They may not be visible at all if {{Lamplight}} has no custom fields set up. They may contain a number of different types of field:
- Date and number fields may be matched as either: 
  - 'Greater than or equal to': people with a value greater (or later) than or equal to the value you specify will be included.
  - 'Less than or equal to': people with a value less (or earlier) than or equal to the value you specify will be included.
  - 'Equal to': only those that match this number or date will be included.
- Multi-select fields:
  - 'Does have': people who do have and exact match to all the options that you select will be included. 
  - 'Does not have': people who do not have any of the options that you select will be included.
  - 'Has at least one of': people who have at least one (maybe more) of the options that you select will be included.
  - 'Has at least two of': people with at least two (maybe more) of the options that you select will be included.
  - 'Has at least three of': people who have at least three of the options that you choose will be included.

### {Work}}

The fields in this tab allow you to filter for {{people}} based on the {{work}} records in their profile. If you want to find {{people}} that have attended sessions based on dates, you first need to set the dates, then you need to specify the {{work}} area(s) you want to filter on. You can also choose to find {{people}} that have not attended at certain periods. So, for example:

**To identify {{user}}s attending at least one session of Life Skills after 1st April 2018 and before 31st March 2019:**

- For date 1 (this will be your 'from' date), choose 'Fixed date' from the drop-down and select to 1st April 2018. Date 1 will **include** the date that you choose.
- For date 2 (your 'to' date) choose 'Fixed date' from the drop-down menu, then select 1st April 2019. Date 2 **does not include** the date you specify, so if you want records to 31st March, you have to specify 1st April.
- You want to find records between those dates, so next go to the 'Number of records in profile **between** date 1 and 2' (the middle line from the next set of three). You are looking for people with at least one record between those dates, so choose 'Greater than or equal to' on the drop-down, then type '1' in the text box after it.
- Underneath that, you are looking for people who attended, so from the drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
-  In the drop-down box for 'Role', select '{{User}}'. This will exclude other attendees, such as {{staff}} or {{volunteer}}s.
- Finally, under {{workarea}}, choose 'Life Skills'.


![Automatic {{group}}s - {{work}} records tab example 1](11.1.0b.png)

**To identify {{staff}} attending an Initial Assessment between 1st April 2019 and 30th September 2019 (equivalent to people attending between Start of Q1 2019 and End of Q2 2019)**
- For date 1 (this will be your 'from' date), choose 'Start Quarter 1' from the drop-down, then select '2019' from the box below that.
- For date 2 (your 'to' date) 'End Quarter 2' from the drop-down, then '2019' from the box below that.
- You want to find records between those dates, so next go to the 'Number of records in profile **between** date 1 and 2' (the middle box from the next set of three). You are looking for people with at least one record between those dates, so choose 'Greater than or equal to' on the drop-down, then type '1' in the text box after it.
- Underneath that, you are looking for people who attended, so from the drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
-  In the drop-down box for 'Role', select '{{Staff}}'. This will exclude other attendees, such as {{user}}s or {{volunteer}}s.
- Finally, 'Initial Assessment' is a {{subworkarea}}, so first choose 'Support'under {{workarea}}, then 'Life Skills'.


![Automatic ((group))s - {{work}} records tab example 2](11.1.0c.png)


XXXXX UP to here XXXXX

To identify new users - people attending the centre after 1st April 2013 that had never attended before then:

![Automatic {{group}}s - {{work}} records tab example 3](103e.png)

To identify attendees who have completed the course - service users who in Q3 2013 attended at least 6 sessions of the 10 session Gardening course

![Automatic {{group}}s - {{work}} records tab example 4](103f.png)



The **{{Outcome}}** fields tab is where you can search for {{people}} based on their outcome scores for a particular measure. You can look for {{people}} with a particular score, those who have changed over time or those who have maintained a score for a specified period of time. This will let you set up {{group}}s like '{{people}} who have gained a job and have sustained it for 6 months'. Bear in mind here that {{Lamplight}} treats yes-no {{outcome}}s as 1 - 0 (ie a 'yes' is stored as 1, and a 'no' as a 0), so to find {{people}} that have answered 'yes' to a particular {{outcome}} you'll need to enter the 'Outcome score' as 'Equal to' '1'. 

The fields in the **{{Referral}}** and **{{Grant}}** tabs work like those in the {{work}} tab, allowing you to search for {{people}} involved in a {{referral}} or {{grant}} record respectively. 

**{{Case}}s**:  This tab allows you to create a list of {{people}} who are involved in a particular case by case name, category or within a given timeframe.

When you have added all criteria, click the 'save' button in the bottom-right.


###### core module


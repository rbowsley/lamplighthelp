# 16.12.1  <i class="fas fa-tools"></i> Global Settings: {{People}} and {{Org}}s

> The '{{People}} and {{org}}s' tab contains options concerning how to record information about {{people}} and relationships in profiles, how the search function works and displays results, and how new profiles are created




### Profiles

#### Do you want to keep {{user}} names anonymously?   

   If this option is not enabled, the name is a required field for creating a {{user}} profile. With this option enabled, {{user}} profiles can be created without entering a name. Profiles can be identified by their {{Lamplight}} ID numbers, which are automatically assigned. They can still be created with names as well, so it is possible to have a mixture of profiles that are and are not anonymous.

#### Do you want to store middle names?  

   This option enables an extra field on profiles, and when adding a new profile, for the entry of middle names.

#### Do you want to be able to store details of relationships between different {{people}}? 

   This option enables profiles to be linked by relationship. For more information on relationships in {{Lamplight}}, see [16.6.3 System Administration: Relationships](/help/index/p/16.6.3).

#### Should the "default contact" box be ticked by default?   

   This option appears when linking two profiles and determines whether the profile is to be used as the default contact. This is how it appears when adding a relationship:

   ![Default Contact when Adding a Relationship](16.12.1a.png)
 
   For example, if you want general communications with an {{org}} to be addressed to the Receptionist, you need to tick this box when you link the Receptionist’s profile to the {{org}} profile.  We would advise you to only have one profile set as the default contact for each {{org}}, otherwise the system will not always make the desired selection when addressing communications. 

   Note that this option only takes effect when the setting ‘Do you want to use relationships between {{people}} in {{work}} and other records?’ is enabled (see below).

#### Do you want to be able to add new profiles from the relations tab?  

   This option enables you to create profiles using the ‘Find {{people}}’ box when adding relationships to profiles. If the {{person}} or {{org}} that you need to link to does not have a profile, you can enter the name in the 'Find people' box as you are creating the relationship. The new profile will then be created using just this name. You will need to navigate to the profile afterwards to update the profile with other details. It will automatically have been created as a {{person}} who is a {{user}}, so if this is not their role type you can change it on the their 'Contact details' tab.

   If this option is enabled and you create a profile in this way, you will be asked to confirm that this is what you intended:

![Creating a New Profile Confirmation](16.12.1b.png)
 
#### Do you want to use relationships between {{people}} in {{work}} and other records?   

   If you choose to enable this option then there will be a ‘default contact’ tickbox when you set up a new relationship. 

#### Do you want to allow multiple default contacts for a single profile?   

   When you set up a relationship you have the option to create the {{person}} you are linking as a ‘default contact’ for the profile it is linked to (see ‘Should the "default contact" box be ticked by default?’ above). Ticking this ‘multiple default contacts’ box will allow you to link many profiles to a single {{person}} or {{org}}, each as the default contact. 

   It is advised to only have one profile set as the default contact for each profile, otherwise the system will not always make the desired selection when addressing communications. Only tick this box if you have a specific reason for needing multiple default contacts for a single profile.

#### What types of {{people}} do you want to store details of?   

   Lamplight has two types of profiles enabled by default: ‘{{person}}’ and ‘{{org}}’. If you do not need to use both, this is where you can disable the type you don’t need.

   In addition, you can enable ‘family’ profiles. These can be useful if you need to record specific details about a family as well as the individuals in that family. For example, whether the family has access to a car, or details of their immigration status or housing situation. If you do decide to use family profiles, you may also want to link family members to the family profile using relationships.  Note that ther term 'family' can be [translated](/help/index/p/16.16.0) if needed, so they don't have to be families - this is just the default terminology.

#### What roles may different {{people}} or {{org}}s have?   

   Every profile in Lamplight is given a role. The default options for these roles are:
    - {{user}}.
    - {{staff}} member.
    - {{contact}}.
    - {{org}}.
    - {{funder}}.
    - {{volunteer}}.

   If you don’t need to use any one of these, you can disable it here to avoid extra options when adding new profiles.

#### How to check for duplicates when entering new {{people}}?    

   This option determines how the system searches for similar profiles to prevent the creation of duplicates. The options are:
   
   - Names which sound similar but may be spelled differently.  This can help catch typos or different spellings (e.g. Claire, Clare, Clair) but expects English words, so detection of duplicates from other languages may not work as effectively.  This is the default and will generally be the best option.
    - Names which contain other names.  This will search the full names for your new profile name
	- Identical names.  Will search (non case sensitively) for exactly the same name in your system.
	
If you have the ['my user restriction'](/help/index/p/16.12.6) duplicates will still be detected, but operators affected will not be able to resolve it as they won't have access to the existing possible duplicates.

<<<<<<< HEAD:source/16-12-1_Global_Settings-_People_and_Orgs.markdown
=======
![How to Search for Duplicates](16.12.1c.png)
 
>>>>>>> 0e65355ac6181e0c406b6862567511f0a9ab98b2:source/16-12-1_Global_Settings-_People_and_Orgs.markdown
#### Do you want to enable autosave on profile custom tabs?   

   This option can be useful if you often forget to save the information you have entered into custom profile tabs before you leave the page. It will save automatically in this case. Be careful enabling this option though, because any information you delete or overwrite will be lost automatically, without requiring you to click the save button. There is no way to cancel or undo once it has autosaved.

### Searching

#### How do you want searches to display the results?   

   This option determines how matches are displayed in the search bar at the top-right corner of the screen.
     - The default option, first name, surname and ID number will look like this:

     ![Displaying First Name, Surname and ID Number](16.12.1d.png)

     - Changing the options to full name, postcode, email address, for example, will mean that the same results are displayed like this:

     ![Displaying Full Name, Postcode, Email Address](16.12.1e.png)
 
#### Do you want to show relationships in the main menu search?    

   Profiles in Lamplight can be linked using relationships. This option allows profiles to be displayed in the search bar according to the relationships that profile has. It is similar to the way in which linked profiles are displayed when searching to add attendees to {{work}}, {{outcome}} or {{referral}} records.

   Enabling this option can help you to distinguish between {{people}} who have similar names, or to quickly identify the name of someone related to another profile. It will show the results like this:

   ![Showing Relationships in the Main Menu](16.12.1f.png)

#### If you type a number in the search, do you want to search the Lamplight IDs?   

   As well as searching by name, you can use the search box to find profiles based on date of birth, email address or ID number. You can also search for case ID numbers or {{work}} record ID numbers.

   A profile’s ID number is automatically generated by Lamplight whenever you add a new profile to the system. If you regularly search using numbers but do not use the ID numbers generated by Lamplight, you may want to disable this option to limit the number of search results.

#### Sort search results by...  

   This option determines how profiles are listed when you look at {{people}} in tables, for example if you go to {{people}} -> view -> {{user}} from the main menu. It does not affect how results are listed in searches from the search box in the top right corner of the screen. 

   ![Searching for People from the Main Menu](16.12.1g.png)
 
   You can sort search results by first name, surname or full name.

#### Minimum number of search results before searching again  

   In the main menu search bar, Lamplight will try different ways of searching until it finds some results. By default, it will only try additional searches if it does not find any results.

   You can change this so that additional searches will be carried out if there are fewer than three results, for example. By putting a larger number here, {{Lamplight}} will search for more records, but searching will be slower.

The top-right search bar works in the following way:
    - If you enter a number, it will search for profile IDs, {{work}}/{{referral}}/{{outcome}} IDs, or case IDs.
    - If you enter an email address, it will search email addresses.
    - If you enter a date, it will search custom date fields in profiles (so you can search by date of birth, for example)
    - If your search term looks like a UK postcode, it will search in the postcode field.
    - If you enter a series of letters, it will search full names.

Once this first search is done:
    - If the number of results is below the limit set in this configuration option, it will then search the Alternative Name field in profiles.  
    - If the number of results is still below this limit, it will search for names that sound like the search term provided.


### Adding New Profiles

#### Do you want to split up the "{{person}} -> add" main menu item?    

   This option decides how new profiles are created from the main menu.

   By default, this option is enabled, which means that when you click '{{people}} -> add {{person}} in the main menu, you are offered a list of the roles enabled in your system. Once you click on a role, it will be selected in the ‘New {{person}}’ screen you see next.

   ![Adding a Client](16.12.1h.png)
   
   ![Adding a Client Screen 2](16.12.1i.png)
 
   If you choose to disable this option, clicking {{people}}>add {{person}} in the main menu takes you straight to the ‘New {{person}}’ screen without first selecting a profile type or role. You will need to these on the next screen.
This setting does not change the options available, it just changes how they are viewed in the main menu.

   ![Adding a Profile Not Split](16.12.1j.png)
   
   Please note: if you add essential fields when creating a profile (see below) then the menu will be split by default, whichever option you have chosen here.
   
#### Which fields are essential (required to add a profile) for a {{person}}?    
   Essential fields are those that must be completed to create a profile. Each of these ten drop-down menus lists all the fields available in {{person}} profiles. Selecting a field from one of these menus will add it to the initial profile creation page, which must be completed before a new profile can be saved.

   For example, selecting ‘Email’ from the list will show the ‘Email’ field in the initial profile creation page.

   ![Adding Email as an Essential Field](16.12.1k.png) 
   
   ![Email Added as an Essential Field when Creating a Profile](16.12.1l.png)

   It will still also be visible and editable in the tab that it was created in.

   If you try to save a profile without completing the essential fields, you will be presented with an error message like the one below and you will need to complete the field on order to proceed with the profile creation.

   ![Problem with Profile Creation](16.12.1m.png)
 
   It's a good idea to limit the number of essential fields to those which are critical to your work. Staff members will not be able to save a new profile without all of the essential fields, and if there are too many this can cause issues for workflow.

   Note that if you specify an essential field, profile types will automatically be split in the main menu (see 'Do you want to split up the "{{person}} -> add" main menu item?' above).

#### Which fields are essential (required to add a profile) for an {{org}}?  

   As with the essential fields required for a {{person}}'s profile, you can use the drop-down menus here to specify which fields are required when you add an {{org}}'s profile. 


###### core module



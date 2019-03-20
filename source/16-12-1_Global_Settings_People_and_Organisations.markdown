# 16.12.1 Global Settings: {{People}} and {{Org}}s

> The {{People}} and {{org}}s tab contains options concerning how to record information about {{people}} and relationships in profiles, how the search function works and displays results, and how new profiles are created.


### Profiles

- **Do you want to keep {{user}} names anonymously?**   

   If this option is not enabled, the name is a required field for creating a {{user}} profile. With this option enabled, {{user}} profiles can be created without entering a name. Profiles can be identified by their lamplight ID numbers, which are automatically assigned. They can still be created with names as well, so it is possible to have a mixture of profiles that are and are not anonymous.

- **Do you want to store middle names?**   

   This option enables an extra field on profiles, and when adding a new profile, for the entry of middle names.

- **Do you want to be able to store details of relationships between different {{people}}?** 

   This option enables profiles to be linked by relationship. For more information on relationships in {{Lamplight}}, see the Appendix at the end of this guide.

- **Should the "default contact" box be ticked by default?**   

   This option appears when linking two profiles and determines whether the profile is to be used as the default contact. This is how it appears when adding a relationship:

   xxxxxx Picture here xxxxxx
 
   For example, if you want general communications with an {{org}} to be addressed to the Receptionist, you need to tick this box when you link the Receptionist’s profile to the {{org}} profile. You might not want this box to be ticked when linking the profile of their Finance Manager to the {{org}} profile.

   It is advised to only have one profile set as the default contact for each {{org}}, otherwise the system will not always make the desired selection when addressing communications. To avoid unexpected results, it may be advisable to disable this option, which is enabled by default, in global settings.

   Note that this option only takes effect when the setting ‘Do you want to use relationships between {{people}} in {{work}} and other records?’ is enabled.

- **Do you want to be able to add new profiles from the relations tab?**   

   This option enables you to create profiles using the ‘Find {{people}}’ box when adding relationships to profiles. If the desired profile does not exist, it will be created using just the name you entered the box. You will need to navigate to the profile afterwards to update the profile with other details. It will automatically have been created as a {{person}} who is a {{user}}.


   If this option is enabled and you go to create a profile in this way, you will be presented with a message letting you know that you are about to create such a profile.

   xxxxxx Picture here XXXXXX
 
- **Do you want to use relationships between {{people}} in {{work}} and other records?**   

   If this option is not ticked then you will not be able to use default contacts in your system. If you choose to enable this option then there will be a ‘default contact’ tickbox when you set up a new relationship. 

- **Do you want to allow multiple default contacts for a single profile?**   

   When you set up a relationship you have the option to create the {{person}} you are linking as a ‘default contact’ for the profile it is linked to (see ‘Should the "default contact" box be ticked by default?’ above). Ticking this ‘multiple default contacts’ box will allow you to link many profiles to a single {{person}} or {{org}}, each as the default contact. 

   It is advised to only have one profile set as the default contact for each profile, otherwise the system will not always make the desired selection when addressing communications. Only tick this box if you have a specific reason for needing multiple default contacts for a single profile.

- **What types of {{people}} do you want to store details of?**   

   Lamplight has two types of profiles enabled by default: ‘{{person}}’ and ‘{{org}}’. If you do not need to use both, this is where you can disable the type you don’t need.

   In addition, you can enable ‘family’ profiles. These can be useful if you need to record specific details about a family as well as the individuals in that family. For example, whether members of that family have access to a car, or details of their immigration status or housing situation. If you do decide to use family profiles, you may also need to think about linking family members to the family profile using relationships.

- **What roles may different {{people}} or {{org}}s have?**   

   Every profile in Lamplight is given a role. The default options for these roles are:
    - {{service user}}
    - {{staff}} member
    - {{contact}}
    - {{org}}
    - {{funder}}
    - {{volunteer}}

   If you don’t need to use any one of these, you can disable it here to avoid complication when adding new profiles.

- **How to check for duplicates when entering new {{people}}?**   

   This option governs how the system searches for similar profiles to prevent the creation of duplicates. The options are shown below.

   xxxxxx Picture here xxxxxx
 
- **Do you want to enable autosave on profile custom tabs?**   

   This option can be useful if you often forget to use the save button to save the information you have entered into custom profile tabs. It will save automatically in this case. Be careful enabling this option though, because any information you delete or overwrite will be lost automatically, without requiring you to click the save button. There is no way to cancel or undo once it has autosaved.

### Searching

- **How do you want searches to display the results?**   

   This option governs how information is displayed in the search bar in the top-right corner of the screen when matches are found.

   The default options, first name surname and ID number will cause results to be displayed like this:

   XXXXX Picture here XXXXXX

   Changing the options to full name, postcode, email address, for example, will cause the same results to be displayed like this:

   XXXXXX Picture here XXXXXX
 
- **Do you want to show relationships in the main menu search?**   

   Profiles in Lamplight can be linked using relationships. This option allows profiles to be displayed in the search bar according to the relationships that profile has. It is similar to the way in which linked profiles are displayed when searching to add attendees to {{work}}, {{outcome}} or {{referral}} records.

   Enabling this option can help you to distinguish between {{people}} who have similar names, or to quickly identify the name of someone related to another profile. It will cause the results to appear as in this example:

   xxxxxx picture here xxxxxx

- **If you type a number in the search, do you want to search the Lamplight IDs?**   

   As well as searching by name, you can use the search box to find profiles based on date of birth, email address or ID number. You can also search for case ID numbers or {{work}} record ID numbers.


   A profile’s ID number is automatically generated by Lamplight whenever you add a new profile to the system. If you regularly search using numbers but do not use the ID numbers generated by Lamplight, you may want to disable this option to limit the number of search results.

- **Sort search results by...**   

   This option does not affect how results are listed in searches from the search box in the top right corner of the screen. Rather, it governs how profiles are listed in the tables you see when you use the main menu items under {{people}}>view, for example when viewing all service users.

   xxxxxx Picture here xxxxxx
 
   You can sort search results by first name, surname or full name.

   xxxxxx Picture here xxxxxx
 
- **Minimum number of search results before searching again**   

   In the main menu search bar, Lamplight will try different ways of searching until it finds some results. By default, it will only try additional searches if it does not find any results.

   You can change this behaviour, so that additional searches will be carried out if there are fewer than three results, for example. By putting a larger number here, you will get more search results, but searching will be slower.

   The top-right search bar works in the following way:
    - If you enter a number, it will search for profile IDs, {{work}}/{{referral}}/{{outcome}} IDs, or case IDs.
    - If you enter an email address, it will search email addresses.
    - If you enter a date, it will search date fields in profiles.
    - If it looks like a postcode, it will search in the postcode field.
    - If you enter a series of letters, it will search full names.
    - If the number of results is below the limit set in this configuration option, it will then search the Alternative Name field in profiles.  
    - If the number of results is still below this limit, it will search for names that sound like the search term provided (using the Metaphone algorithm).


### Adding new profiles

- **Do you want to split up the "{{person}} -> add" main menu item?**   

   This option governs the way that new profiles are created from the main menu.

   By default, this option is enabled, which means that when you click {{people}}>add {{person}} in the main menu, you are offered a list of the roles enabled in your system. Once you click on a role, it will be selected in the ‘New {{person}}’ screen you see next.

   xxxxxx Picture here xxxxxx
 
   If you choose to disable this option, clicking {{people}}>add {{person}} in the main menu takes you straight to the ‘New {{person}}’ screen, but no profile type will be selected. You will need to enter one here instead of selecting one through the main menu.
This setting does not change the options available, it just changes how they are viewed in the main menu.

   xxxxxx Picture here xxxxxx
 
- **Which fields are essential (required to add a profile) for a {{person}}?**   
   Essential fields are those that must be completed to create a profile. Each of these ten drop-down menus lists all the fields available in {{person}} profiles. Selecting a field from one of these menus will add it to the initial profile creation page, which must be completed before a new profile can be saved.

   For example, selecting ‘Email’ from the list as shown here…

   xxxxxx Picture here xxxxxx

   … will show the ‘Email’ field in the initial profile creation page as shown here (it will still also be visible and editable in the tab that it was created in):

   xxxxxx Picture herexxxxxx

   If you try to save a profile without completing the essential fields, you will be presented with an error message like the one below and you will need to complete the field on order to proceed with the profile creation.

   xxxxxx Picture here xxxxxx
 
   It might be advisable to limit the number of essential fields to those critical to your work, otherwise creating new profiles will require a lot of information without which the staff member will not be able to save the profile.

   Note that if you specify an essential field, profile types will automatically be split in the main menu and this will override the split up the "{{person}} -> add" main menu item option.

- **Which fields are essential (required to add a profile) for an {{organisation}}?**   

   As with the essential fields required for a {{person}} profile, you can use the drop-down menus in this setting to specify which fields are required to add an {{organisation}} profile. 


###### core module



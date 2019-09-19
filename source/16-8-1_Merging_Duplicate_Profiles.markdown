# 16.8.1    <i class="fa fa-user"></i> Merging Duplicate Profiles

> Every {{person}} or {{org}} should only have one profile in {{Lamplight}}. If you find you have duplicates these can be merged by a System (or {{Project}}) Administrator



### To Merge Profiles

Duplicate profiles may both contain data relating to the same {{person}}, and which needs to be merged into a single profile.  Some of this data may be inconsisent - perhaps they moved house but only one address was updated.  There's no reliable way for a computer to know which data is accurate, so {{Lamplight}} provides you with a way to identify potential duplicates; decide if they are they same {{person}}; and then go through and choose what data to keep, and how to combine it.

Different data can also be combined in different ways.  A single person can only have one date of birth, so if each profile has a different one, you'll need to choose which to keep.  But a single person can attend many {{work}} records, so {{Lamplight}} will allow you to combine the records from both profiles into one, if you want to.

 There are three steps in merging profiles:
 - Identify possible duplicates
 - Compare data in the two duplicate profiles and choose how to merge it into one profile
 - Archive the other profile
 
 To get started:
- Go to 'admin -> System administration -> Data Management'.
- Click on  'Find and merge duplicate profiles'.

On this page you can choose what criteria you use to find duplicates, whether it's all or part of a profile name or address.  You can choose several criteria if you get a lot of 'false positives' (profiles that aren't really duplicates) when you search using just one.  For example, if you work with family members, searching by surname or address may show lots of profiles that have the same address but which aren't duplicates.  In that case you'd also need to use first name as a criteria.

![Search for Duplicates By](16.8.1a.png)

Once the system has searched for profiles, all possible duplicates using the criteria you selected are listed in the **destination profile** drop down.  The destination profile is the one that you want to merge all your data into - the one you'll keep in your system.

![Duplicate Profiles](16.8.1b.png)

When you select a profile to merge the **source profile** drop down will change to show the possible duplicate profiles.  The source profile is the one that you are copying (some) data from, and which you'll archive once you have finished.  There may be more than one possible source profile, but if so you'll need to deal with them one at a time.  Select a source profiles from the drop-down.

![Duplicate Profile Lists](16.8.1c.png)
 
The source profile (which is the one that will be archived once the profiles are merged) is always the one listed on the right. The destination profile (which is the one which you will keep once the profiles are merged) will always be the one on the left. The data that you see on the left-hand side of the screen once when you are merging sections is the data that will ultimately be kept in the profile for that person.

Once you've selected the profiles to merge, you will see sections for different types of information. At the bottom of each of these  you will be asked what information you want to keep, and how to combine it.

  ![Information to Keep](16.8.1d.png)

The options for each section are:
    - **Discard source data**. {{Lamplight}} will not merge the data, simply discard anything that appears in the right-hand column.
    - **Overwrite destination with source data**. {{Lamplight}} will populate the left-hand column with information from the right, so any information saved in the left-hand column will be lost. This includes where a field has been filled in in the left-hand column but not on the right. It will become an empty field.
    - **Copy source to destination; on conflict keep newest**. Information from the right-hand column will be used to populate the left-hand column. Where there is already information in the column on the left, {{Lamplight}} will use whichever data was entered most recently.
    - **Only copy source data where the destination is empty**. {{Lamplight}} will use data from the right-hand column to populate the left-hand one, but only where there is no data already entered.
    - **Combine data from the two profiles**. It is only possible to choose this option for sections where you can add to information rather than replacing it, for example relationships or {{activity}} records. This will create one list from the entries of both left-hand and right-hand columns.

When you have made your selection click on the 'Merge this section now' button.

Once each section has been merged you can return to the 'View and merge profiles' section near the top and archive the source profile.


Why not watch our video?

<iframe src="https://player.vimeo.com/video/279249527" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>


##### Tags
Profile
GDPR

###### core module

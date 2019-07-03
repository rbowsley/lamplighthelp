# 16.8.3 Deleting a Profile

> System Administrators can permanently delete profiles. Once they are deleted they cannot be reinstated, even by Lamplight staff

### To Delete a Profile

**Finding Which Profiles to Delete

- Go to ‘admin -> system administration -> Data Management -> PERMANENTLY delete data’.
- Scroll to the end of this page to see the options for choosing the profiles for deletion.
  - Delete members of a {{group}}. You will need to have set this {{group}} up already - you can then select it from the drop-down menu. For more on creating {{group}}s, see [11.0.0 {{Group}}s](/help/index/p/11.0.0).
  - Find profiles that have been archived. This will give you a list on the next page of all archived profiles on your system. You can choose from there which you would like to delete.
  - Find single profile. This is a search box which you can use to find the profile you want to delete. Like the standard {{Lamplight}} search box, it will not find archived profiles. 
  - Find profiles that have not been updated in the last.... If you choose this option, you can specify a timescale, and {{Lamplight}} will look for profiles where the profile fields, custom fields and {{activity}} records have not been edited or updated in that time. You will see a list on the next page to choose from. 
- Once you have chosen how to look for profiles to delete, click 'next'.
- Tick the names of the profiles that you want to delete at the top of the next page. If it is a long list and you want to delete them all, you can tick the checkbox next to the name at the top of the list, then hold down the shift key on your keyboard, scroll down the list to the last name and tick the checkbox next to the last name. This will automatically select all of the profiles for you.   

**Choosing Which Details to Delete**

- Decide which details to delete. There are a number of options:
  - Name and address only. This will delete these details, but the rest of the profile information and {{activity}} records will remain on the system.
  - Name, address and relationships. As above, but this option will also delete any relationships so that they do not show in profiles.
  - Name address, relationships, custom fields, and remove from work etc. records. In addition to the information in the previous options, choosing this one will delete all profile data and remove the {{person}} or {{org}} from all attendance tables in {{activities}} records. This includes {{work}}, {{referral}}s, {{outcome}}s, {{grant}}s etc. The records themselves will not be deleted.
  - Name, address, relationships, custom fields and delete any work etc. records completely that they are listed on. This is the same as the option above, but instead of deleting the {{person}} or {{org}} from the {{activity}} records, the record itself will be deleted. This means that it will not be counted in any future {{report}}s.
- Click in the box at the bottom of the list to confirm that you want to permanently delete the profiles and data you've selected. 
- Click 'delete forever'.
- The next screen will confirm the data that has been deleted.

![Confirmation of Deletion](16.8.3a.png)

###### core module

# 27.1.1    {{Staff}} Management Module: the Hierarchy

> To ensure personnel files are kept secure and confidential a hierarchy system can be put in place. This will allow only {{staff}} members and their manager to view their full profile. 


Due to the potentially sensitive nature of the data held within the {{Staff}} Management Module (pay details, annual leave etc), {{staff profiles}} are governed by a hierarchy. System Administrators will need to put this in place.

By default, the only person who can see a profile is the database operator whose profile it is. Once you structure the hierarchy, this  allows managers in the same branch to see (and report) on those who are below them on the branch. Any other {{staff}} member who views a colleagues profile, who does not have access rights, will only be able to view the 'normal' tabs, and not the {{Staff}} Module tabs.

**To Structure the Hierarchy**

- Go to the System Administration menu by clicking on Admin in the main menu, and then choosing ‘System Administration’ in the menu bar itself. 
- Find the ‘Manage database operators’ section, and click on ‘view and edit staff hierarchy’. All the people who have a ‘staff’ profile in Lamplight appear in this list, not only database operators. 
- To set the hierarchy, click, hold and drag the person who is managed, over the name of the person who is their manager and release the mouse.

   - **Scenario 1** - Joseph Bloggs manages Arlene Gee
   Left click, hold and drag the name ‘Arlene Gee’ over the top of ‘Joseph Bloggs’ and release the mouse. Joseph Bloggs can now see the staff management module tabs of his own profile AND Arlene Gee. Arlene Gee, Hermione Granger and Jolly Jepson can only see their own profiles.
 
   - **Scenario 2** - Joseph Bloggs manages Arlene Gee and Jolly Jepson
   Left click, hold and drag the name ‘Jolly Jepson’ over the top of ‘Joseph Bloggs’ and release the mouse. Joseph Bloggs can now see the staff management module tabs of his own profile AND Arlene Gee AND Jolly Jepson. Arlene Gee, Hermione Granger and Jolly Jepson can only see their own profiles.
 
   - **Scenario 3** - Arlene Gee manages Hermione Granger
   Left click, hold and drag the name ‘Hermione Granger’ over the top of ‘Arlene Gee’ and release the mouse. Joseph Bloggs can now see the staff management module tabs of his own profile AND Arlene Gee AND Jolly Jepson AND Hermione Granger. Arlene Gee can now see the staff management module tabs of her own profile AND Hermione Granger. Hermione Granger and Jolly Jepson can only see their own profiles
 

###### staff module


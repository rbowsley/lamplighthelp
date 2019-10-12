# 20.2.8 Charge Module: Creating a {{Work}} Record-based Charge Rule

> {{Work}} record charge rules will calculate the charge based on the {{work}} record involved. Rates can be based on {{workarea}}s and {{subworkarea}}s, {{staff}} attending, and the location(s) used



With a {{work}} record charge you can specify amounts to charge depending on the {{workarea}}s and {{subworkarea}}s chosen in the record, plus {{staff}} attending and location used. The different aspects of calculations for these rules are cumulative, so the total charge will be {{workarea}} charges + {{subworkarea}} charges + {{staff}} charges + location charges. If a {{work}} record has a {{workarea}} and two {{subworkarea}}s, and each of these has a charge against them in the rule, the total charge will be the sum of these three (plus {{staff}} and locations). 

Each of these charges is applied to everyone in full. This means that if you are applying a charge for the location or staffing, 100% of this will be charged to each attendee (unless other rules, such as attendance role charge rules, are set up to mitigate this).

### How to Set Up a {{Work}} Record Charge Rule

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click the 'Create new {{work}} record charge rule' button. 

![Setting up a {{work}} record charge rule](20.2.8a.png)

- Section [20.2.1 Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields. (It's likely that you will want to tick the 'Should previous rules apply if there is no match using this rule?' box.) 


#### {{Workarea}}s and {{Subworkarea}}s
- First enter any rates for {{workarea}}s and {{subworkarea}}s. 
   - If you choose £ in the drop-down, a fixed charge will be used regardless of previous rules in the policy or the duration of the {{work}} record. 
   - Choosing a percentage will calculate a percentage of the amount calculated by previous rules in the policy. 
   - Choosing 'hour' will calculate an hourly rate based on the duration of the {{work}} record. You can mix and match these in the rule. 
- If you leave any {{workarea}}s and {{subworkarea}}s blank they will be counted as '0' (i.e. no charge). Whether you want to do this depends how you intend to use the rule. 
   - If this is a 'base' rule that will appear first or second in policies, it will be fine to leave some blank, particularly {{subworkarea}}s. 
   - If this is a 'supplement' type rule - adding on to our basic rates set in another rule - then you will either want to tick the 'should previous rules apply' box, or enter 100% to all entries which you'd otherwise leave blank. 

#### {{Staff}} and {{Volunteer}} Rates
- The {{staff}} section can use information from staff contracts, if the staffing module has been enabled on your system. If it is, then you are able to use either their 'wage' rates, or their 'charge-out' rates. {{Lamplight}} will use the contract in force on the date of the {{work}} record. These hourly rates will then be multiplied by the duration of the {{work}} record, for each member of staff attending - note that they need to be recorded as attendance type 'attended' and role 'staff' on the {{work}} record. 
- If you do not wish to use these rates, you can also either specify an hourly rate or a fixed rate (regardless of {{work}} record duration). These rates will be applied for each member of staff shown as attending in the {{work}} record attendance table. Choose which of these you want to apply from the drop-down menu, then fill in the rate in the box below.

#### Location Rates
- Location rates use information set up in the 'locations' list in system administration. 
   - To add and edit locations go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> Work Records -> Locations'. 
   - Find the relevant location in the list and click on 'add contact details'. 
   - Save your changes before exiting.   
   - For more on locations see our video - [52.1.1 How to Add and Edit Locations](/help/index/p/52.1.1).
- {{Lamplight}} will apply the charges for each location used in the {{work}} record. 
- When you are finished, click 'save' in the bottom-right hand corner. You will be taken back to the charge settings menu, and you'll see your new rule in the 'charge rules' section. 


###### charge module


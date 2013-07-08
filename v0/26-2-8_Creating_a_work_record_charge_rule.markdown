# 26.2.8    Creating a {{work}} record charge rule

> To set up a {{work}} record charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create new {{work}} record charge rule' button. 

To set up a {{work}} record charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create new {{work}} record charge rule' button. 

![Setting up a {{work}} record charge rule]({{imgpath}}249a.png)

Section [26.2.1  Setting up charge rules - general points](/help/index/v/{{version}}/p/26.2.1) explains the 'name' and 'previous rules' fields. It's likely that you will want to tick the 'Should previous rules apply if there is no match using this rule?' box. 

{{Work}} record charge rules will calculate the charge based on the {{work}} record involved. Rates can be based on {{workarea}}s and {{subworkarea}}s, {{staff}} attending, and the location(s) used. These rates can be fixed, percentages or hourly rates - in which case the duration of the {{work}} record is used. 

The different aspects of these calculations are culmulative. So the total charge will be {{workarea}} charges + {{staff}} charges + location charges. In addition, {{subworkarea}}s are culmulative, so if a {{work}} record has a {{workarea}} and two {{subworkarea}}s, the total charge will be the sum of these three (plus {{staff}} and locations). 

To set up the rule, enter first any rates for {{workarea}}s and {{subworkarea}}s. If you choose £ in the drop-down, this fixed charge will be used, regardless of previous rules in the policy or the duration of the {{work}} record. Choosing a percentage will calculate a percentage of the amount calculated by previous rules in the policy. Choosing 'hour' will calculate an hourly rate based on the duration of the {{work}} record. You mix and match these in the rule. 

If you leave any blank they will be counted as '0' (i.e. no charge). Whether you want to do this depends how you intend to use the rule. If this is a 'base' rule that will appear first or second in policies, it will be fine to leave some blank, particularly {{subworkarea}}s. However if this is a 'supplement' type rule - add a little bit to our basic rates set in another rule - then you will either want to make sure that the 'should previous rules apply' box, or enter 100% to all entries which you'd otherwise leave blank. 

The staffing section can use information from staff contracts, if the staffing module has been enabled on your system. If it is, then you are able to use either their 'wage' rates, or their 'charge-out' rates. {{Lamplight}} will use the contract in force on the date of the {{work}} record. These hourly rates will then be multipled by the duration of the {{work}} record, for each member of staff attending - note that they need to be recorded as attendance type 'attended' and role 'staff' on the {{work}} record. 

If you do not wish to use these rates, you can also either specify an hourly rate or a fixed rate (regardless of {{work}} record duration). These rates will be applied for each member of staff attending. 

Location rates use information previously set about the location in the admin menu; you can set 'internal' and 'charge-out' rates for each location. {{Lamplight}} will add these up for each location used in the {{work}} record. 

When you are finished, click 'save' in the bottom-right hand corner. You will be taken back to the charging menu, and you'll see your new rule in the 'charge rules' section. 

###### charge module


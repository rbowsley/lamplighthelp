# 20.2.7 Charge Module: Creating a {{Group}} Bands Rule

> The {{group}} bands rule allows you to charge people based on their membership of a particular auto {{group}}



The {{group}} bands rule allows you to charge people based on their membership of a particular auto {{group}}. This will be useful in order to provide an 'unwaged' rate, for example, or to charge based on the turnover of the organisation attending. 

A rule can contain several bands, each based on a {{group}} - you will need to set up the auto {{group}}s you are using first (see section [11.1.0  Creating an Auto{{Group}}](/help/index/p/11.1.0) for details). 
- In the 'unwaged' example, you would need a {{group}} that checks for unwaged status. 
- In the 'turnover' example, you would need one auto {{group}} for each band. The first auto {{group}} would be (for example) 'turnover below £100,000', the second 'turnover between £100,001 and £250,000' and a third 'turnover greater than £250,001'. 
- When you have created your auto {{group}}s, you can set up the rule. 

### To set up a {{group}}-based charge rule:
- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click the 'create a new {{group}} bands charge rule' button. 
- Section [20.2.1  Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields. (It's likely that you will want to tick the 'Should previous rules apply if there is no match using this rule?' box.) 
- Click on the first cell of the table to give the band a name. 
- Click on the second cell ('{{Group}} to check membership of') and select the {{group}} you wish to use from the drop- down list. 
- In the rate cell, enter a number or a percentage. 
   - Numbers are interpreted as amounts of money. 
   - Percentages are of any amount calculated by a previous rule. So to charge unwaged attendees a flat £10, regardless of any previous rules, you would enter 10 in the rate box. To charge 20% of the full rate (calculated by previous rules), you would enter 20% in the rate box. 
   - If you use percentages, this should not be the first rule in a policy. This is because it will have no previous amount to calculate from, so all charges will come out as 0 (as any % of 0 is 0). 

![A simple {{group}}-bands based charge rule](20.2.7a.png)

- To add another band, click the 'add row' button on the right of the table. 
- Someone cannot be in two different bands even if they belong to more than one {{group}}. You will need to put the bands in order of priority as {{Lamplight}} will stop looking through them as soon as it has made a match. For example, if you are charging £15 for family carers to attend a session, and £10 for someone with a disability, you would want to put the band for the people with a disability higher in the table so that a person appearing in both those {{group}}s would be charged the lower rate. 
- When you have finished, click 'save' in the bottom-right hand corner. You will be taken back to the charge settings menu, and you'll see your new rule in the 'charge rules' section. 

###### charge module


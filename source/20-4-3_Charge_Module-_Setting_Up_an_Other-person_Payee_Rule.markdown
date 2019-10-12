# 20.4.3 Charge Module: Setting Up an Other-person Payee Rule

> An other-person payee rule will allocate an amount to be paid by a third-party, for example, a funder. For example, you may have a contract with a Local Authority that will pay a proportion of the training costs for people living in their area



The other-person payee rule lets you decide who will pay the charge for a session even if they are not in the attendance table. You can use this to apply the correct billing for Local Authority funded services for example, or to apportion costs of services to different funders for reporting purposes, for example.

To add an other-person payee rule:

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'. 
- Click on the 'Create new other person payee rule' button. 

![Setting Up an Other-person Payee Rule](20.4.3b.png)

To create the rule, you need to add one or more bands (rows) by clicking on the cells in the table and adding the details.
   - {{Person}} to charge: who should pay whatever amount is due? This field is required: when you click on the cell and get the text box, start typing the name of the {{person}} or {{org}} (it will need to be someone with a profile already in the system). {{Lamplight}} will search as you type: click on the name you want when it appears in the drop-down list. 
   - Rate: either a percentage (e.g. 35%) or a fixed amount (e.g. 23 - this will be £). This field is required. 
   - Attendance type: selecting any attendance types will mean that the {{person}} or {{org}} you have chosen will only be charged if the {{person}} listed on the {{work}} record matches one of the attendance types. For example, you may not want to charge a funder for a place if the {{person}} cancelled their place. If you leave this blank, attendance type will not be considered in this filter (i.e. the charge will be passed on regardless of attendance type). 
   - Role: selecting any roles will mean that the {{person}} or {{org}} you specify will only be charged if the {{person}} listed on the {{work}} record matches one of the selected roles. For example, you may only want the funder to be charged for {{user}}s, not {{staff}} or {{volunteer}}s. If you leave this blank, the role will not be considered for this filter. 
   - Only charge if attendee is member of {{group}}: click to select a {{group}} from the drop-down box if you want to add custom filters. Using this will enable you, for example, to allocate payments on a geographical basis (e.g. Westminster Council only pays for attendees living in Westminster). You will need to set the {{group}} up before you can apply it to the rule (for more on this see [12.0.0 Groups](/help/index/p/12.0.0)).
   - Which attendees to try and match to this {{group}}: when using linked profiles on the {{work}} record (e.g. Matt Parker, Lamplight Database Systems), you can choose whether to match the first listed profile, second listed, or either. You may need to use this if (continuing the example) Westminster Council have agreed to pay for places where the organisation represented (i.e. Lamplight Database Systems) is based in Westminster, regardless of where the particular individual lives. Use 'either' for most cases - this will make a match based on information from both linked profiles. For more on linked records, see [16.6.3 System Administration: Relationships](/help/index/p/16.6.3).
   - Continue to subsequent payees if this one matches? You can add rows to this table: you might have one for Westminster, and another for Brent, for example. In this case, if you click on 'no' {{Lamplight}} will not need to check whether to allocate payments to Brent Council if there's already been a match with Westminster. But if you have different criteria for different funders, and attendees could be partially funded from a number of sources, you will want to select 'yes'. 


If you want to add several (potential) payees in a single rule, you can click 'add row' to add a subsequent payee. The order is important again: {{Lamplight}} will check and allocate amounts in the order of the table, and if you choose 'no' to 'continue to subsequent payees' it will not check subsequent rows as soon as it has a match for each attendee. 

Alternatively, if you want to use payees in different combinations for different policies then create them as separate rules, each with a single payee (row in the table).  

![Charge Attendance to Other People Payee Rule](20.4.3a.png)

When you have finished, click 'save' in the bottom-right hand corner. You will return to the charge module admin screen, and will be able to see the rule listed. 


###### charge module


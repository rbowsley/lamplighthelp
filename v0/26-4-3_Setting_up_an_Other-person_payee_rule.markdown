# 26.4.3    Setting up an Other-person payee rule

> To add an other-person payee rule, click 'admin' -> system administration and click on 'set up charge module rules and policies'. Click the 'create new other person payee rule' Button. 

To add an other-person payee rule, click 'admin' -> system administration and click on 'set up charge module rules and policies'. Click the 'create new other person payee rule' button. 

![Setting up an other-person payee rule]({{imgpath}}254a.png)

The screenshot shows a rule set up with two 'bands', which are explained below. An other-person rule will allocate an amount to be paid by a third-party, for example, a funder. For example, you may have a contract with a Local Authority that will pay a proportion of the training costs for people living in their area. 

In fact, you may want to do this even if you do not have this type of contract but wish to apportion costs of services to different funders, for reporting purposes. 

To create the rule, you need to add one or more bands, by clicking on the cells in the table and setting the details.

  1. {{Person}} to charge: who should pay whatever amount is due? This field is required: when you click on the cell and get the text box, start typing the name of the {{person}}. {{Lamplight}} will search as you type: click on the name of the {{person}} when they appear on the drop-down list. 
 2. Rate: either a percentage (e.g. 35%) or a fixed amount (e.g. 23). This field is required. 
  3. Attendance type: selecting any attendance types will mean that the {{person}} will only be charged if the {{person}} listed on the {{work}} record matches one of the attendance types. If you leave this blank, no filter will be applied (ie the charge will be passed on regardless of attendance type). You may not want to charge a funder for a place if the {{person}} did not attend the {{work}} record. 
  4. Role: selecting any roles will mean that the {{person}} will only be charged if the {{person}} listed on the {{work}} record matches one of the selected roles. If you leave this blank, no filter will be applied. 
  5. Only charge if attendee is member of {{group}}: click to select a {{group}} from the drop-down box if you want to add custom filters. Using this will enable you, for example, to allocate payments on a geographical basis (e.g. Westminster Council only pays for attendees living in Westminster). 
  6. Which attendees to try and match to this {{group}}: when using linked profiles on the {{work}} record (e.g. Matt Parker, Lamplight Database Systems), you can choose whether to match the first listed, second listed, or either. You may need to use this if (continuing the example) Westminster Council have agreed to pay for places where the organisation represented (i.e. Lamplight Database Systems) is based in Westminster, regardless of where the particular individual lives. Use 'either' for most cases. 
  7. Continue to subsequent payees if this one matches? You can add rows to this table: you might have one for Westminster, and another for Brent, for example. In this case {{Lamplight}} will not need to check to allocate payments to Brent Council if there's already been a match with Westminster. But if you have different criteria for different funders, you will want to select 'yes'. 

If you want to add several (potential) payees in a single rule, you can click 'add row' to add a subsequent payee. The order is important again: {{Lamplight}} will check and allocate amounts in the order of the table, and if you choose 'no' to continue to subsequent payees will stop processing the rule. 

Alternatively, you could in many cases create a series of rules, each with a single payee (row in the table). If you want to combine different payees in different combinations in different policies, then create them as separate rules. Otherwise, create a single rule with several payees (rows in the table). 

When you are finished, click 'save' in the bottom-right hand corner. You will return to the charge module admin screen, and will be able to see the rule listed. 

###### charge module


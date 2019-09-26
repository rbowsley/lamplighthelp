# 20.4.1 Charge Module: Setting up an Attendee Payee Rule

> An attendee payee rule specifies that the profile listed in the {{work}} record pays for their charges for the session



An attendee payee rule is very simple: the person or organisation listed on the {{work}} record pays their charges. All you need to do is specify the amount.

To add an attendee payee rule:

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'. 
- Click the 'Create new attendee payee rule' button. 

![Setting up a {{work}} record charge rule](20.4.1a.png)

Give the rule a name. Make it clear what this rule does - you will use this to pick rules to add to a policy later.

Add a rate to be paid: this can be a percentage or a fixed amount (in £s). 
   - If you specify a percentage, this will be a percentage of the remaining amount to be paid. As a simple example, you might set up a rule that has a rate of 100%, and then create a payee policy containing just this rule. This will mean that the {{person}} attending will pay the full amount as calculated by the charge policy used. 
   - However, if you have another payee policy with a rule that allocates 25% to another organisation (a funder, for example), and then the 'attendee pays 100%' rule, the attendee will be charged 100% of the outstanding amount - that is, 75% of the total amount - as 25% has already been charged to the funder. In other words, you can't create payments for more than the overall amount charged. 
   - It is possible, however, to create policies that do not allocate the full charge. An attendee payee rule of 50% as the only rule in a policy will mean that only 50% of the charges calculated are allocated. To avoid this, you might want to create an 'attendee pays 100%' rule that is added as the last rule in all policies, to ensure that any 'underbilling' is allocated to the person attending. 

When you have finished click 'save' in the bottom right hand corner. You will return to the charge module admin menu. 

![Attendee Payee Rule](20.4.1b.png)


###### charge module


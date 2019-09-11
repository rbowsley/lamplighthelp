# 20.4.2 Charge Module: Setting Up a Body-type Payee Rule

> A body type rule allocates an amount to be paid based on the 'type' of the person or organisation listed - {{person}}, {{org}} or {{family}} (if you have them enabled in your system)



You can use this type of rule if you add {{people}} to {{work}} records using linked relationships. For example, if Matt Parker is linked to Lamplight Database Systems as an employee, and this type of relationship has been enabled to be used in linked records in your system, then you can add 'Matt Parker, Lamplight Database Systems' to the {{work}} record, instead of just 'Matt Parker' or 'Lamplight Database Systems'. In this example you will most likely want to send the bill to Lamplight Database Systems, rather than Matt Parker personally, so you can use a body-type payee rule set to 'organisation' to ensure that it is the organisation that pays. (For more on linked records, see [16.6.3 System Administraton: Relationships](/help/index/p/16.6.3).)

To add a body-type payee rule:

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'. 
- Click the 'Create new body-type payee rule' button. 

![Setting up a body- type payee rule](20.4.2a.png)

- Give the rule a clear name, so that when you come to create a policy you will understand what this rule does.
- Choose the type which will pay the charge - {{person}}, {{org}} or {{family}}.
- Choose the rate that they will pay. This can either be an amount (in £s), or a percentage of the overall calculated charge.
   - If you specify a percentage, this will be a percentage of the remaining amount to be paid. As a simple example, you might set up a rule that has a rate of 100% for the {{org}}, and then create a payee policy containing just this rule. This will mean that the {{org}} will pay the full amount as calculated by the charge policy used.  
   - However, if you have another payee policy with a rule that allocates 25% to a particular funder for example, followed by the '{{org}} pays 100%' rule, the {{org}} will be charged 100% of the outstanding amount - that is, 75% of the total amount - as 25% has already been charged to the funder. In other words, you can't create payments for more than the overall amount charged.
   - It is possible to create policies that do not allocate the full charge. If you set up a body-type rule which allocates 50% of the charge, and is the only rule in a policy, this will mean that only 50% of the charges calculated are allocated. 
- If you want the {{org}} to pay rather than the individual, you will need to make sure that you add {{org}}s to the {{work}} record not just the individual. If the organisation is not stated, {{Lamplight}} will not be able to allocate the amount to pay. 

![A Body-type Payee Rule](20.4.2b.png)

- When you have finished click 'save' in the bottom right hand corner. You will return to the charge module admin menu. 


###### charge module


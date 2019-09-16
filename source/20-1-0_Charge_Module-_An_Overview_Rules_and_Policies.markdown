# 20.1.0 Charge Module: An Overview Rules and Policies

> A charge rule contains a single logic-based step to calculate part of a charge, or decide how to allocate that charge. A policy is a combination of rules



A policy is made up of one or more rules. There are different types of rules that look at the {{work}} record and the {{person}} listed to calculate charges and payees. Charge policies and payee policies use a similar approach. 

When you save a {{work}} record, {{Lamplight}} will look at each {{person}} attending, and cycle through each rule in the policy, checking any criteria and acting on the result. 

### Charge Policies

The very simplest charge rule is a flat-rate rule. This will apply a set amount (for example £50) to everyone listed on a {{work}} record. So if you just charge a flat-rate all the time, that's a good place to start. 

![Flat-Rate Charge Rule](20.1.0b.png)

However, you probably don't want to charge your staff members for attending. So you could create a second rule, a role-based charge rule. This lets you specify how much to charge based on the role of the {{person}} in that particular {{work}} record. You could either specify fixed amounts, or percentages in this rule: 100% for service users and 0% for staff and others. 

![Role Based Charge Rule](20.1.0a.png)

You can now combine these two rules in a charge policy, with the flat-rate rule first and the role-based rule second. 

![Summer Outing Charge Policy](20.1.0c.png)

When you apply this policy, {{Lamplight}} will look at each {{person}} listed on the {{work}} record. It will apply the first rule, and charge them £50. It will then apply the second rule: if they are listed as a Service user charge 100% of £50 (i.e. £50), if not charge 0% of £50 (i.e. £0). 

### Payee Policies

Payee policies work in a similar way: you set up rules and add them to policies. 

Rules within a policy are processed in turn. Payee policies recognise that the {{person}} attending isn't always, or entirely, the {{person}} that pays for that service. As a simple example, someone attending training on behalf of their employer would expect their employing organisation to pay. 

![Employer Pays Rule](20.1.0d.png)

A more complicated example is where funders have agreed to pay some or all of the costs for some or all of the people attending. A Local Authority may only pay for places taken by people living in their area; a funder may only pay for places if that person has a particular characteristic. You set up payee rules that apply this logic, and if the criteria are fulfilled, Lamplight will apply the charge to the appropriate payee. 

![LA Pays for Attendees with Long Term Health Conditions](20.1.0e.png)

To summarise: charge policies are made up of one or more charge rules. These rules calculate a total charge for a particular {{person}} attending a particular {{work}} record. The payee policy, consisting of one or more payee rules, determines who should pay the charge, and where appropriate can break it up into smaller amounts, each to be paid by a different {{person}} or {{org}}. 


###### charge module


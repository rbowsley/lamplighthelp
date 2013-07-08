# 26.1.1    Overview of charge module rules and policies

> A rule contains a single logic step to calculate part of a charge, and how to allocate that charge. A policy is a combination of rules. 

A Policy is made up of one or more Rules. There are several different types of rules that look at the {{work}} record and the {{person}} listed to calculate charges and payees. Charge policies and Payee policies use a similar approach. 

When you save a {{work}} record, {{Lamplight}} will cycle through each {{person}} attending, and cycle through each rule in the policy, checking any criteria set and acting on the result. 

The very simplest charging rule is a flat-rate rule. This will apply a set amount (let's say £50) to everyone listed on a {{work}} record. So if you just charge a flat-rate all the time, that's a good place to start. 

However, you probably don't want to charge your staff members for attending. So you could create a second rule, a role-based charge rule. This lets you specify how much to charge based on the role of the {{person}} on that particular {{work}} record. You could either specify fixed amounts, or percentages in this rule: 100% for service users and 0% for staff and others. 

You can now combine these two rules in a charge policy, with the flat-rate rule first and the role-based rule second. When you apply this policy, {{Lamplight}} will look at each {{person}} listed on the {{work}} record. It will apply the first rule, and charge them £50. It will then apply the second rule: if they are listed as a Service user charge 100% of £50 (i.e. £50); if not charge 0% of £50 (i.e. £0). 

Payee policies work in a similar way: you set up rules and add them to policies. Rules within a policy are processed in turn. Payee policies recognise that the {{person}} attending isn't always, or entirely, ther {{person}} that pays for that service. As a simple example, someone attending some training on behalf of their employer would expect their employing organisation to pay. A more complicated example is where funders have agreed to pay some or all of the costs for some or all of the people attending. A Local Authority may only pay for places taken by people living in their area; a funder may only pay for places if that person has a particular characteristic. You set up payee rules that apply this logic, and if the criteria are fulfilled the payee will be charged the appropriate amount. 

To summarise: charge policies are made up of one or more charge rules. These rules calculate a total charge for a particular {{person}} attending a particular {{work}} record. The payee policy, consisting of one or more payee rules, breaks this total charge up into smaller amounts, each to be paid by a different {{person}}. 

###### charge module


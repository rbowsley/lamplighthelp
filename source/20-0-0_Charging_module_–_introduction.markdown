# 20.0.0 Charging Module: Introduction

> The Charging Module allows you to set charges for attending a {{work}} session, and then decide who should pay that charge 

The Charging Module is about calculating charges for different sessions. There is a great deal of flexibility in how this is done, and the payments due can be split between different {{people}} and {{org}}s. Once payments have been allocated they can be batched up into invoices which can then be exported as a csv and used for billing and credit control purposes. 

The Charging Module is designed so that it's really quick and easy to use on a day to day basis. This does mean that setting it up takes a little time. All policies are set up by a System or {{Project}} Administrator.

For day-to-day use, when adding a {{work}} record you will see a {{charge}} tab, which lets you choose a charging policy and a payee policy for the record. 

![Charging policy in {{work}} record](1222a.png)

Charging policies determine how much each {{person}} attending should be charged; payee policies determine who should pay this charge. 

### Creating Policies

Both charge and payee policies can take various factors into account in their calculations. The policies you create are up to you - there are no standard policies in the system.  

A simple session might:
- have a charging policy that charges everyone £50.
- have a payee policy that says that the {{person}} attending pays the full amount. 

A more complex charging policy might: 
- Use an hourly rate for the {{workarea}} chosen, a fixed amount for the location used, and the hourly rate for the staff present.
- Charge any unemployed {{person}} attending a fixed rate of £10.
 - Give a discount for {{people}} booking online before a certain date.
 - Only charges {{user}}s attending the full amount; staff are charged nothing and {{people}} that do not turn up are charged 50%.

A more complicated payee policy might say: 
- If the {{person}} attending lives in Westminster, charge Westminster Council 50% (we have a contract with them).
- If the {{person}} attending has a visual impairment, charge £30 to a private Foundation that has given us a grant.
- Charge any remainder to the {{org}} linked to the person that attended.

When you create a {{work}} record using these policies, {{Lamplight}} will calculate the amounts and payees, and they will appear on the {{charge}} tab of the relevant profiles, with a summary shown on the {{work}} record. 

By using these policies it is possible that the amount charged for someone attending a session will not be the same as they pay: indeed often the {{person}} attending will not pay anything. In these cases, the 'charge' should be thought of as the total amount paid by all parties (i.e. funders) for that person attending. 

### Stacking Policies

You can set-up mutiple rules in the same policy, and determine the order in which they apply. This is important, as rules will be applied to attendees in the order in which they are listed. For example, if the first rule in a policy charges a {{vol}} £10 based on their attendance, no further rules will be processed for that {{vol}}.  This is very important to bear in mind as you read through the rest of this help section.


###### charge module


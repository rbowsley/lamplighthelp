# 20.2.1 Charge Module: Overview of Charge Rules

> The common features of charge rules, and some tips to make sure that they do what you intend



Almost all charge rules have two fields in common:

  1. Rule name.
  
  2. Should previous rules apply if there is no match using this rule?
  
  ![Common Fields for Charge Rules](20.2.1a.png)
  
### Rule Name

The 'rule name' is what you'll see when adding rules to policies. Please remember that one rule can be re-used in several different policies, so it'll be easier if the name describes what it does, rather than how you think you might use it. So 'base flat 80' to describe a flat-rate charge rule that charges £80 is better than 'training standard rate'. 

### Should Previous Rules Apply

Imagine we have set up two rules: a flat-rate charge rule (for £50) and a role-based charge rule that says 'service users pay 100%'. We set up a policy that uses these two rules; the flat-rate rule first, then the role-based rule. 

When we come to use the policy, {{Lamplight}} will look at each {{person}} listed. First it will set the charge to £50. Then it will check their role. 
  - If it is 'service user', then the final charge will be 100% of £50. 
  - If it is something else, say a staff member, what should {{Lamplight}} do? We've only set our rule to do anything with service users.   
  - If the 'should previous rules apply' box was ticked, then if the rule does not match (because it's a member of staff), the previous (flat-rate) rule will apply, and they'll be charged £50. 
  - If the box was not ticked, the rule does not match and the previous flat-rate rule does not apply, so they will be charged £0. 

In general, it's likely that for attendance and role-based rules, you will not want previous rules to apply. For other types of rule, it's more likely that you will want previous rules to apply. 

Note that this does not apply to flat-rate rules as by their nature they apply to everyone, so there is no possibility that there will not be a match. In other words, as previous rules only apply where the current one doesn't, they can never apply to flat-rate rules. 

###### charge module


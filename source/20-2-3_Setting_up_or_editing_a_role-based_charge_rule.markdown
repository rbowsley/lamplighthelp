# 20.2.3 Setting Up a Role-based Charge Rule

> Role-based charge rules are where you can apply different charges depending on the role in which someone attends a session

You may want to set different charges for {{people}} attending the same session. For example, a training session could be full-price for {{user}}s, but half price for your {{vol}}s. 

To set up a role-based charge rule:
- Go to admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies.
- Click the 'create new role-based charge rule' button. 

![Setting up a role-based charge rule](20.2.3a.png)

Section [20.2.1  Setting Up Charge Rules: General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields. 

For each role type, you can set an amount or a percentage. If you set an amount (e.g. £50) then they will be charged that amount: this is not culmulative from previous rules. If you set a percentage (e.g. 75%), this will use an amount from a previous rule. If you use percentages, you probably don't want to use the rule first in the policy. You could do, but it will come out as 0 (as n% of 0 is 0). 

You can mix and match fixed amounts and percentages for different roles. In general you are likely to want to combine both attendance roles and types: see section [26.2.5  Setting up or editing an attendance/role based charge rule](/help/index/v/{{version}}/p/26.2.5) for how to do this. 

When you are finished, click 'save' in the bottom- right hand corner. You will be taken back to the charging menu, and you'll see your new rule in the 'rules' section. 

###### charge module


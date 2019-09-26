# 20.2.3 Charge Module: Setting Up a Role-based Charge Rule

> Role-based charge rules are where you can apply different charges depending on the role in which someone attends a {{work}} record





You may want to set different charges for {{people}} attending the same session. For example, a training session could be full-price for {{user}}s, but half price for your {{volunteer}}s. 

To set up a role-based charge rule:
- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click the 'create new role-based charge rule' button. 

![Setting Up a Role-based Charge Rule](20.2.3a.png)

Section [20.2.1  Setting Up Charge Rules: General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields. 

For each role type, you can set an amount or a percentage. 
   - If you set an amount (e.g. £50) then they will be charged that amount: this is not cumulative from previous rules. 
   - If you set a percentage (e.g. 75%), this will use an amount from a previous rule. 
   - Don't use percentages if this is going to be the first rule in the policy as the amount will always come out as 0 (as any % of 0 is 0). 

You can mix and match fixed amounts and percentages for different roles. 

![A Role-based Rule](20.2.3b.png)

When you have finished, click 'save' in the bottom- right hand corner. You will be taken back to the charge settings menu, and you'll see your new rule in the 'rules' section. 

It often makes sense to combine both attendance roles and types: see section [20.2.5  Setting Up an Attendance/Role-based Charge Rule](/help/index/v/{{version}}/p/20.2.5) for more details. 


###### charge module


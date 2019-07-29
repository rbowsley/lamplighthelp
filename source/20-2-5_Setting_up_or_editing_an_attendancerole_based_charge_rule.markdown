# 20.2.5    Setting up or Editing an Attendance/Role-based Charge Rule

> This allows you to combine information and set up charge rules using data on attendance (booked, cancelled, no show etc.) alonside the different roles ({{staff}}, {{vol}}, {{user}}etc.) 

To set up an attendance/role-based charge rule:
- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'. 
- Click the 'Create new attendance/role based charge rule' button. 

![Setting up an attendance-role based charge rule](20.2.5a.png)

- Section [20.2.1  Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields.
- Beneath that, the table shows attendance types down the left, and roles along the top. Each cell represents the combination (e.g. '{{user}} that attended'). For each of these you can specify an amount or a percentage. 
   - If you set an amount (e.g. £50) then they will be charged that amount: this is not cumulative from previous rules. 
   - If you set a percentage (e.g. 75%), this will use an amount from a previous rule. 
   - If you use percentages, this should not be the first rule in a policy. This is because it will have no previous amount to calculate from, so all charges will come out as 0 (as any % of 0 is 0).
- You can mix and match fixed amounts and percentages for in attendance cells of the table. 

![Role/Attendance-based Charge Rule](20.2.5b.png)

- When you have finished, click 'save' in the bottom- right hand corner. You will be taken back to the charging menu, and you'll see your new rule in the 'charge rules' section. 


###### charge module


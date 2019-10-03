# 20.2.9 Charge Module: Creating a Custom Attendance Fields Charge Rule

> These charge rules use data from custom attendance table fields



You may have custom attendance table columns in your {{Lamplight}} system. If this is the case, you can use them to set up charge rules.

To set up a custom attendance fields charge rule:

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'. 
- Click the 'Create new custom attendance fields charge rule' button. 

![Setting up a custom attendance fields charge rule](20.2.9a.png)

Section [20.2.1 Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields.

Beneath that you will see a table with the different fields available to use. For each of these you can specify an amount or a percentage to charge. 
   - If you set an amount (e.g. £50) then they will be charged that amount: this is not cumulative from previous rules. 
   - If you set a percentage (e.g. 75%), this will calculate the amount to charge based on a previous rules. 
   - If you use percentages, this should not be the first rule in a policy. This is because it will have no previous amount to calculate from, so all charges will come out as 0 (as any % of 0 is 0).
You can mix and match fixed amounts and percentages in the table. 

![Role/Attendance-based Charge Rule](20.2.9b.png)

When you have finished, click 'save' in the bottom- right hand corner. You will be taken back to the charge settings menu, and you'll see your new rule in the 'charge rules' section. 


###### charge module

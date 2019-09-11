# 20.2.4 Charge Module: Setting Up an Attendance-based Charge Rule

> An attendance-based charge rule is where you can set different rules depending on whether a person attended a session, cancelled or did not turn up etc.




To set up an attendance-based charge rule:
- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click on 'Create new attendance-based charge rule'.

![Setting Up an Attendance-based Charge Rule](20.2.4a.png)

- Section [20.2.1  Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields. 
- You can set an amount or a percentage for each attendance type. 
   - If you set an amount (e.g. £50) then they will be charged that amount: this is not cumulative from previous rules. 
   - If you set a percentage (e.g. 75%), this will use an amount from a previous rule. 
   - If you use percentages, this should not be the first rule in a policy. This is because it will have no previous amount to calculate from, so all charges will come out as 0 (as any % of 0 is 0). 
- You can mix and match fixed amounts and percentages for different attendance types. 

![Attendance-based Charge Rule](20.2.4b.png)

- When you have finished, click 'save' in the bottom-right hand corner. You will be taken back to the charge settings menu, and you'll see your new rule in the 'charge rules' section.

In general you are likely to want to combine both attendance roles and types: see section [20.2.5  Setting Up an Attendance/Role Based Charge Rule](/help/index/p/20.2.5) for more information. 

 
###### charge module


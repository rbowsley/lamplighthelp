# 20.2.6 Charge Module: Creating a Date-based Charge Rule

> A date-based charge role calculates charges based on the date that a person is added to the {{work}} record. You can also opt to specify attendance type and role



A date-based charge rule will calculate charges based on when a {{person}} was added to the {{work}} record, or when they booked. It can optionally also filter for attendance types and roles. This allows you to add 'early bird discounts' and 'late cancellation penalty' type rules. 

To set up a date-based charge rule:
- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click the 'create new date-based charge rule' button. 

![Setting up a date-based charge rule](20.2.6a.png)

- Section [20.2.1 Setting Up Charge Rules - General Points](/help/index/p/20.2.1) explains the 'name' and 'previous rules' fields.
- You can add several date bands to the rule, each with different settings. The first date band to match will be used.
- Click on the date (by default today's date) in the first row. 
- A calendar will appear: select the date you want. 
- Do the same for the 'date to'. 
- Click in the next cell, 'Comparison date', where you will see two choices: date booked or date added. 
   - 'Date added' is the date this attendance was last updated (when you edit a record it 're-adds' them to the record). For late cancellation fee type rules, you will want to choose 'date added'. 
   - For early-bird discounts, you will want to choose 'date booked'. This is when they were first entered into the attendance table.
- Once you have completed this field, click the little save button in the cell. 
- You may optionally also set filters for attendance type and role: again, click the cells in the table and choose those that you need.
- Finally, add a rate. 
   - If it is a number (for example £10) it will be interpreted as a fixed amount of money.
   - If it is a percentage this will be calculated based on the charge already applied in previous rules. 
   - If you use percentages, this should not be the first rule in a policy. This is because it will have no previous amount to calculate from, so all charges will come out as 0 (as any % of 0 is 0). 
- If needed, you can now add additional rows to this table by clicking on the 'add row' button at the end of the last row in the table. Make sure your date bands do not overlap, or you will get unpredictable results. 
- **If you do really need two rules that cover the same date range, you will need to add them as separate rules, and then combine them in the policy.** 

![A Date-based Charge Rule](20.2.6b.png)

- When you have finished, click the 'save' button in the bottom-right corner. 


###### charge module


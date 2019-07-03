# 20.2.6    Creating a Date-based Charge Rule

> To set up a date-based charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create new date based charge rule' button. 

To set up a date-based charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create new date based charge rule' button. 

![Setting up an attendance- role based charge rule](xxxx.png)

Section [26.2.1  Setting up charge rules - general points](/help/index/p/26.2.1) explains the 'name' and 'previous rules' fields. 

A date-based charge rule will calculate charges based on when a {{person}} was added to the {{work}} record, or when they booked. It can optionally also filter for attendance types and roles. We have added this rule with the idea of 'early bird discounts' and 'late cancellation penalty' type rules, although there are bound to be other scenarios. 

You can add several date bands to the rule, each with different settings. The first date band to match will be used. 

To add a particular band, click on the date (by default today's date) in the first row. A calendar will appear: select the date you want. Do the same for the 'date to'. Now you need to choose which date to check against: click in the next cell, the comparison date. You can choose date booked or date added, and then click the little save button. 'Date added' is the date of the last update (when you edit a record it 're-adds' them to the record). For late cancellation fee type rules, you will want to choose 'date added'. For early-bird discounts, you will want to choose 'date booked'. 

You may optionally also set filters on attendance type and role: again click the cells in the table and choose those that you need. Finally, add a rate. This can be a number, in which case it will be interpreted as a fixed amount of money, or a percentage, in which case the charge calculated by previous rules will be multipled by the percentage given. 

If needed, you can now add additional rows to this table. Make sure your dates do not overlap, or you will get unpredictable results. If you do really need two rules that cover the same date range, you will need to add them as separate rules, and then combine them in the policy. When you are done, click the large 'save' button in the bottom-right corner. 

###### charge module


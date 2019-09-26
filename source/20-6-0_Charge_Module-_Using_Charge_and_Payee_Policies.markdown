# 20.6.0 Charge Module: Using Charge and Payee Policies

> Charge and payee policies are used when you create {{work}} records



To add charge and payee policies to {{work}} records:

- If you are using the Charge Module, you will see a 'Charges' tab when creating a new {{work}} records. 
- Open this tab and you will see two drop-downs: 'select charging policy for this record' and 'select payee policy for this record'. 

![Using charge and payee policies](20.6.0a.png)

- If the drop-downs are empty, you will need to create some policies - start at section [22.2.0  Setting Up Rules and Policies](/help/index/p/20.2.0) for help on how to do this. 
- If you can see policies, select the ones you wish to use for this {{work}} record from the drop-downs. 
- When you save the record {{Lamplight}} will calculate charges for each person listed on the attendance tab, and then determine who will pay them. 
- When you save the record you will see this information in summary in the attendance table: 

![Viewing charges and payees in a {{work}} record](20.6.0b.png)

Because the 'other payees' may be any number of {{people}}, they are combined into one column for this view. See section [20.6.1  Viewing payments due from a particular {{person}}](/help/index/p/20.6.1) for help on seeing how charges are allocated. 

If you later edit or delete this record, the charges and payees may also change. If the payments due change, {{Lamplight}} will either update them, or create a credit if the charge has already been invoiced (see section [20.6.2  Creating invoices in bulk](/help/index/p/20.6.2)). 


###### charge module


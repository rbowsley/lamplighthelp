# 20.3.0 Charge Module: Creating a Charge Policy

> To be able to apply charge rules to a {{work}} record you need to create a charge policy. These can consist of a single rule or multiple rules combined together



### To Set Up a Charge Policy

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- You need to have created at least one charge rule before you can create any policies - see section [20.2.0  Setting Up Rules and Policies](/help/index/p/20.2.0) and [20.2.1  Setting Up Charge Rules: General Points](/help/index/p/20.2.1) for more. 
- Click the 'Create new charge policy' button. 

![Setting up a {{work}} record charge rule](20.3.0a.png)

- First you need to give the policy a name: this is how you will choose the correct policy when you're in the {{work}} record, so it needs to be clear.
- The section on the right of the screen shows all the charge rules you have created, and in the centre a space to add the rules you need to your policy. 
- To add a rule to the policy, simply click and hold the mouse button on the rule, drag it to the centre, and release the mouse button. The rule will appear in the central frame. 
- You can add more rules in the same way, and  remove them by dragging them from the central list to the right-hand side. 

![Adding Rules to a Charge Policy](20.3.0b.png)

- The order of the rules is important. Rules will be applied in the order that they are listed. So if you add a flat-rate rule of say £50 as the last in the list, all the other rules that appear earlier will be ignored. 
   - For example, if you want to apply a rate in different percentages to people who have different attendance types, first put in your flat rate rule to give the starting point for charging, then add the rule that shows the different percentages people should pay (attended, 100%; cancelled, 50%; no show, 100% for example). The second rule should have the 'Should previous rules apply' box ticked. {{Lamplight}} will first apply the flat rate rule, then amend this according to the different attendance types. 
   - If you put them into the policy the other way round, {{Lamplight}} will look at the attendance types but have nothing to relate them to, then look at the flat rate and apply it to all attendees the same.
- When you have finished, click the 'save' button in the bottom-right hand corner and you will return to the charge module menu. Your new charge policy will be listed, and is now available to use in {{work}} records. 

### To Edit a Charge Policy

- From the main screen, click on the name of the policy.
- You can add rules and re-order them in the same way as when you are creating a policy.  
- **Note that if you do edit a policy, the changes will not be applied retrospectively - charges already calculated in a {{work}} record will remain as they are. However, if you edit a {{work}} record and keep the same policy, charges will be re- calculated when you save the record. It may be better to create a new policy in these circumstances.**

###### charge module


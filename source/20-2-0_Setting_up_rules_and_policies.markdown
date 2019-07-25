# 20.2.0 Setting up Rules and Policies

> Before you can use charging in {{work}} records your System Administrator will need to set up charge/payee rules and policies

To set up charge/payee rules and policies, go to Admin -> System administration and click 'Set up charge module rules and policies'. You will also see a list of any policies and rules you have already set up. 

### Things to Remember

- You will need to set up rules first, and then policies that use those rules. 
- Each policy must have at least one rule in it.
- Rules can be re-used in different policies. 
- You are likely to only need a small number of policies, although you may need more rules to build them. 
- When creating rules, try to create them so that they can be re-used. 

### Different Types of Charging Rules 

**Flat-rate Rule**

- A flat-rate rule charges everyone the same amount, as specified in the rule.
- See [20.2.2 Setting Up a Flat-rate Charge Rule](/help/index/p/20.2.2)

**Attendance- based Rule**

- An attendance-based rule varies the charge based on the attendance type selected in the {{work}} record (Attended, Did not attend, Cancelled etc). You can specify a fixed amount, or a percentage of the total charge.
- See [20.2.4 Setting Up an Attendance-based Charge Rule](/help/index/p/20.2.4)

**Role-based Rule**

- A role-based rule varies the charge based on the role type selected in the {{work}} record (service user, staff etc). You can specify a fixed amount, or a percentage of the total charge.
- See [20.2.3 Setting Up a Role-based Charge Rule](/help/index/p/20.2.3)

**Attendance/Role Based Rule**

- Attendance-role based rules are a combination of the two above; amounts or percentages to be charged are based on both attendance and role type. 
- See [20.2.5 Setting Up an Attendance/Role-based Charge Rule](/help/index/p/20.2.5)

**Custom Attendance Field Charge Rule**

- This type of rule is based on any custom columns you have in your attendance table. You can apply a charge based on responses to any checkboxes, radio buttons, select and multi-select fields. Each charge is for a particular response to that field. You can apply a fixed charge or percentage of the amount calculated in other rules. Any charges you apply are cumulative, so if an attendee meets all the different criteria you set, they will be charged the total of each of the amounts set. 
- See [20.2.9 Setting Up a Custom Attendance Field Charge Rule](/help/index/p/20.2.9)

**Date-based Rule**

- A date-based charge rule calculates an amount based on the date someone booked on the {{work}} record, or the date of the most recent update. This can optionally also use attendance type and role. Date-based rules let you create 'early-bird discount' rules, or 'late cancellation penalty' rules, for example.
- See [20.2.6 Setting Up a Date-based Charge Rule](/help/index/p/20.2.6)

**{{Group}}-bands Rule**

- A {{group}}-bands charge rule checks if a {{person}} is a member of a particular {{group}}, and if they are applies the rate specified. You can create charge bands, each based on a different {{group}}. For example, you could create an 'unwaged rate' rule. You will need to set up the {{group}}s you want to use first.
- See [20.2.7 Setting Up a {{Group}}-bands Charge Rule](/help/index/p/20.2.7)

**{{Work}} Record Charge Rule**

- A {{work}} record rule calculates charges based on details from the {{work}} record: {{workarea}}s, locations, and staff. 
   - Different rates can be set for each {{workarea}} and {{subworkarea}}. 
   - Staff costs can be fixed amounts, amounts per hour, or use wage or charge-out rates from the staff members contract details (if you have the Staff Management Module). {{Lamplight}} will check for those listed as staff attending on the {{work}} record, and calculate rates for those people. 
   - Location rates can use the hourly internal rate or hourly charge-out rate for the locations used. 
These calculations are cumulative: if you select them all in the rule, the amount charged will be the {{workarea}} amount, plus any {{subworkarea}} amounts, plus the rates for all staff attending, plus the rates for all locations used. 
- See [20.2.8 Setting Up a Work Record Charge Rule](/help/index/p/20.2.8)

### Different Types of Payee Rules 

**Attendee Payee Rule**

- An attendee payee rule charges the {{person}} attending a fixed amount or percentage of the total charge.
- See [20.4.1 Setting Up an Attendee Payee Rule](/help/index/p/20.4.1)

**Body-type Payee Rule**

- A body-type payee rule charges based on the type of {{person}} attending ({{person}}, {{org}} or {{family}}). These rules can be used to charge the organisation attending, rather than the individual. 
- See [20.4.2 Setting Up a Body-type Payee Rule](/help/index/p/20.4.2)

**Other Person Payee Rule**

- An other-person payee rule assigns some or all of the charge to a completely different {{person}} or {{org}}. You can specify criteria to decide whether the different {{person}} should pay, based on attendance type, role, and {{group}} membership. These rules are how you assign charges to funders, Local Authorities etc. If you use {{group}}s you will need to set them up first. 
- See [20.4.3 Setting Up an Other-Person Payee Rule](/help/index/p/20.4.3)

**Other Person Relationship Payee Rule**

- Like the above rule, you can assign some or all of the charge to a different {{person}} or {{org}}. In this case it is a profile linked to {{person}} or {{org}} in the {{work}} record by a specific type of relationship. This rule can be useful for setting up policies where employers will pay for their staff's attendance at training, for example.
- See [20.4.4 Setting Up an Other Person Relationship Payee Rule](/help/index/p/20.4.4)


###### charge module


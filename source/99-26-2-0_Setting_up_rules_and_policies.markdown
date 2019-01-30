# 26.2.0    Setting up rules and policies

> To set up charge/payee rules and policies, go to Admin -> System administration and click 'Set up charge module rules and policies'. You will see a list of any policies and rules you have already set up. 

To set up charge/payee rules and policies, go to Admin -> System administration and click 'Set up charge module rules and policies'. You will see a list of any policies and rules you have already set up. 

You will need to set up rules first, and then set up policies that use those rules. Each policy must have at least one rule in it; rules can be re-used in different policies. You should only need a small number of policies, although you may need more rules to build them. When creating rules, think about whether you can create them in such a way that they can be re-used. 

The different types of charge rules available are: 

**Flat-rate rule**

A flat-rate rule will charge everyone the same amount, as specified in the rule.

**Attendance- based rule**

An attendance-based rule will vary the charge based on the attendance type selected in the {{work}} record (Attended, Did not attend, Cancelled etc). You can specify fixed amounts, or percentages.

**Role-based rule**

A role-based rule will vary the charge based on the role type selected in the {{work}} record (service user, staff etc). You can specify fixed amounts or percentages.

**Attendance/role based rule**

Attendance-role based rules are a combination of the two above; amounts or percentages are based on both attendance and role type. In many cases this will be preferable to using either of the two above.

**Date-based rule**

A date-based charge rule will calculate an amount based on the date someone booked on the {{work}} record, or the date of the most recent update. This can optionally also use attendance type and role. Date-based rules let you create 'early-bird discount' type rules, or 'late cancellation penalty' type rules.

**{{Group}}-bands rule**

A {{group}}-bands charge rule checks if a {{person}} is a member of a particular {{group}}, and applies the rate specified if so. You can create charge bands, each based on a different {{group}}. For example, you could create a rule that charges based on the turnover of the organisation, or an 'unwaged rate' type rule. You will need to set up the {{group}}s you want to use first.

**{{Work}} record charge rule**

A {{work}} record rule calculates charges based on the {{work}} record: {{workarea}}s, locations, and staff. Different rates can be set for each {{workarea}} and {{subworkarea}}s. Staff costs can be fixed amounts, amounts per hour, or use wage or charge-out rates from the staff members contract details (if the staff module is enabled). {{Lamplight}} will check for those listed as staff attending on the {{work}} record, and calculate rates for those people. Location rates can use the hourly internal rate or hourly charge-out reate for the locations used. These calculations are culmulative: if you select them all in the rule, the amount charged will be the {{workarea}} amount, plus any {{subworkarea}} amounts, plus the rates for all staff attending, plus the rates for all locations used. 

The different types of payee rules available are: 

**Attendee payee rule**

An attendee payee rule charges the {{person}} attending a fixed amount or percentage of the total charge.

**Body-type payee rule**

A body-type payee rule charges based on the type of {{person}} attending. These rules can be used to charge the organisation attending, rather than the individual - 

**Other-person payee rule**

An other-person payee rule assigns some or all of the charge to a completely different {{person}}. You can specify criteria to decide whether the different {{person}} should pay, based on attendance type, role, and {{group}} membership. These rules are how you assign charges to funders, Local Authorities etc. If you use {{group}}s you will need to set them up first. 

###### charge module


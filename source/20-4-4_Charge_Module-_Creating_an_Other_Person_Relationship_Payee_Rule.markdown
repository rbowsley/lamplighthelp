# 20.4.4 Charge Module: Creating an Other Person Relationship Payee Rule

> An other person relationship payee rule allows you to set up a rule which charges a third party based on their relationship to the person attending the {{work}} record, for example 'employer'



It may be that you need to charge someone other than the person who attended a {{work}} session for their attendance - it could be their parent or employer, for example. To do this you can set up a rule based on relationships recorded in {{Lamplight}}.

To set up an other person relationship payee rule:

- Go to 'admin -> system administration -> Module Administration -> Charge Module -> Manage charge module rules and policies'.
- Click on the 'Create new other-person relationship payee rule' button.

![Create New Other-person Relationship Payee Rule](20.4.4a.png)

- Name: give the rule a name which can be clearly understood - this is what you will see when choosing rules to add to a policy.
- Relationship: choose the type of relationship that you want. For example, if you want a parent to pay for their child's attendance at an event, choose 'Parent' from the list (this will depend on the types of relationship that you have set up in your system.) You need to ensure that relationships are routinely recorded between profiles, or {{Lamplight}} will not have the information it needs to apply the charge. (For more on recording relationships, see [5.4.0 The Relationships Tab](/help/index/p/5.4.0), and for setting up new relationship types see [16.6.3 System Administration: Relationships](/help/index/p/16.6.3).)
- Attendance type: choose the attendance type for the {{work}} record. If you only want this third person to pay if the {{person}} attended the {{work}} record, choose 'Attended' here. The options you see will depend again on what is set up in your system. If you do not choose an attendance type then {{Lamplight}} will automatically include all of them.
- Attendance role: you can choose here what type of attendee the rule applies to - you may want to limit it to {{user}}s, for example. As with previous fields, the options that you see here may be different to the ones in the example below depending on your system. If you do not choose any role, {{Lamplight}} will include all the different role types in this band.

![Charge Based on Relationship to Attendee](20.4.4b.png)

When you have finished click 'save' in the bottom right hand corner. You will return to the charge module admin menu. 


###### charge module

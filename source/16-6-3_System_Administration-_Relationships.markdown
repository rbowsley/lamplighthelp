# 16.6.3  <i class="fa fa-cogs"></i> System Administration: Relationships

> Relationships are a way of linking profiles to show their connections to one another. For example, they could link a person to an organisation, or a parent to a child



Relationship types are added, edited and deleted in the same way as other drop-down list items previously described - see [16.6.0 System Administration: Lists](/help/index/p/16.6.0).

To add a new one, or edit an old one: 
- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> People and Organisations -> Relation types between people'.

### Inverse Text
Some relationships are reciprocal, with two different sides. For example, a parent and child, or employer and employee.  If the relationship that you are adding is like this: 

- Add the initial relationship (e.g. "parent").
- Double-click on the 'double-click to add' after 'Inverse text'. 
- Add the label for the 'reverse direction' of the relationship (e.g. "child"). 

![Inverse Text](16.6.3a.png)

### Linked Records
If you decide to link records, then {{people}} or {{org}}s who have this type of relationship can be added to the attendance table of an {{activity}} record linked to each other.

- When you use the search box in the 'Attendance' tab of a record, the name of the {{person}} or {{org}} you are searching for will appear there.
- If they have any relationships of this type, there will be another item in the search results list with the name of the {{person}} or {{org}} with whom they have this relationship appearing next to them. 

![Linked Relationships in a {{Work}} Record](16.6.3b.png)

If you choose the linked option (rather than the {{person}}'s name by itself), the record will be attached to both profiles and you will be able to report on the attendance of both of them.  It will count as one attendance in reporting, rather than as two if you added them separately.

One example of when this is useful is if you are running training and people attending are there on behalf of an organisation.  You need to know both the name of the person and their organisation, and they need to be shown together so you know which person is from which organisation.  It's only actually one attendance at the training session, so you need to use linked relationships to record their attendance.


###### core module


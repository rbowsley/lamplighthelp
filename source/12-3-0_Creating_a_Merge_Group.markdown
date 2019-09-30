# 12.3.0  <i class="fa fa-users"></i> Creating a {{Merge group}}

> A {{merge group}} is a {{group}} which is created by combining the members of existing {{group}}s together



{{Merge group}}s change as their component {{group}}s change. Whenever you run a {{merge group}} it will check each of the {{group}}s that it is composed of and give an up-to-date list.  Note that if your component {{group}}s are complex and take time to run, this will slow down your {{merge group}}.

They also remove any duplicates, so if one {{person}} or organisation is present in more than one of the constituent {{group}}s they will only appear once in the {{merge group}}. 

They can be used in the same way that {{manual group}} and {{auto group}}s are.

### To Create a Merge {{Group}}

On the main menu go to '{{Group}}s -> add -> add {{merge group}}s'. 


#### {{Group}} Name Tab

- The name and description are both required fields which has to be filled in before the {{group}} will save.
- Add a name and description of the {{group}} which will help you and other users of the system remember what it is for. The {{group}} will be available for other operators who have access to your system.
- If it is important that you are the only person who can add and remove people from the {{group}}, tick the 'lock this {{group}} for editing' box. That way you can be sure it hasn't changed without you knowing.  Note that if the component {{group}}s are not locked, then others could edit those and change the membership of your {{merge group}}, potentially without you realising.

How to combine the {{group}}s give you three options:

![How to Combine the {{Group}}s](12.3.0a.png)

- Include profiles that are in any of the {{group}}s.  This is like 'adding up' the {{group}}s - add all of the members of all the {{group}}s together into one big {{group}}.
- Only include profiles that are in all of the {{group}}s in the table.  So members of the {{merge group}} have to meet all the criteria of all the component {{group}}s.  This can be useful when you want more criteria than you can specify in a single {{auto group}}.  For example, you may want people who have attended both 'Housing advice' sessions AND 'Benefits advice' sessions this year.  A single {{auto group}} can only do one of those; so create two {{auto group}}s, one for each {{workarea}}, and then the {{merge group}} will find those in both.
- Only include profiles that are in the first list in the table, and are not in any of the others.  Again this can help you combine criteria when it's not possible in a single {{auto group}}.  For example, you could use this to identify {{people}} who have had a {{referral}} in this year, but not a {{referral}} out.  You need to add your {{group}}s in reverse order on the next tab.

### Selecting the constituent {{group}}s 

![Adding a {{merge group}}](183a.png)

To choose the {{group}}s that make up your {{merge group}}, search for them in the usual way:

- On the '{{Group}}s' tab start typing the name of the first {{group}} that you want to include in your merge {{group}}.
- When you find it, click to add it to the table. 
- Continue to find the {{group}}s you want to include until all have been added.
- Each time you add a {{group}} it is added to the top of the table.  If you are selected 'in the first list but none of the others', you will need to add the {{group}}s in reverse order.
- Click 'Save'. 

If you are creating a new {{group}} you will see the members of the {{group}}.  If you are editing you'll see the table of {{group}}s updated with the new number of members.

##### Tags
{{Group}}

###### core module


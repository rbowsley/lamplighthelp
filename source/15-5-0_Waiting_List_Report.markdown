# 15.5.0 {{Waiting List}} {{Report}}

> {{Waiting list}} {{report}}s show you the number of {{people}} on your {{waiting list}}s over time, and the length of time they have been on them



The {{waiting list}} {{report}} provides a number of ways to analyse the numbers and size of your {{waiting list}}s. As with other {{Lamplight}} {{report}}s, there are several tabs that let you define how your data is filtered and presented.

### {{Report}} Filters

The filters are the same as for other {{report}}s. You can restrict the {{report}} to particular {{waiting list}}s if needed here too.

### Projects

If you have more than one {{project}} on your system you can select which {{project}}s you would like to draw data from in this tab. See [14.1.3  {{Report}}s Across Several {{Project}}s](/help/index/p/14.1.3) for more information.

### {{Report}} Presentation

The '{{Report}} presentation' tab gives you different ways to show your data and handle the dates in your {{report}}.

### How to Summarise the Data
You have three options:
- Show overall statistics for the period. This is the default option, giving you a sense of turnover and total waiting times. It returns  the following data for each {{waiting list}} selected:
  - Number of {{people}} at the start of the period: the number of {{people}} on the {{waiting list}} on the first day in the range specified.
  - Number joining the {{waiting list}} in the period: number of {{people}} added between the two dates.
  - Number leaving the {{waiting list}} in the period: number of {{people}} taken off between the two dates.
  - Total number of different {{people}}: one {{person}} may be on the same {{waiting list}} more than once in the date range, but they will only be counted once in this column. This may mean that this figure is different to the previous columns.
  - The mean time spent on {{waiting list}}: the amount of time spent on the {{waiting list}} up until the specifice 'date to', averaged across everyone. This will mean that the figure changes, depending on the 'date to' that you set.
  - The mean time spent on {{waiting list}} (weekdays): a similar calculation to the one above excluding weekends (but not bank holidays etc.)
- Weekly showing average size of {{waiting list}} or Monthly showing average size of {{waiting list}}. These two do the same thing, but over different time spans, showing you how demand for your services has varied week-by-week or month-by-month. This {{report}} gives you: 
  - A table listing the different {{waiting list}}s down the side, and the dates (weeks or months) along the top. 
  - Each figure in the table is the average number of {{people}} on the {{waiting list}} each week (or month). {{Lamplight}} calculates these figures by checking how many {{people}} were on the {{waiting list}} each day, and averaging this over the number of days in the week or month. 
  - Below that is a graph showing the same data. 
  
**How to Handle Dates**  

This section allows you to use the dates you've selected on the '{{Report}} filters' page in one of three ways:
- Show for everyone on the {{waiting list}} between the two dates. This is the default option and will give the number of {{people}} on the {{waiting list}} at any point between the dates including:
  - {{people}} who were on it before the start and after the end date; 
  - {{people}} who were put on it during the time period; 
  - {{people}} who were on it at some point during the time period but were taken off before the end date. 
- Show for everyone added to the {{waiting list}} between the two dates. This will include:
  - {{people}} who were added to the {{waiting list}} between the two dates and were still on it after the end date.
  - {{people}} who were added and left between the two dates.
- Show for everyone removed from the {{waiting list}} between the two dates. This will include:
  - {{people}} who were already on the {{waiting list}} before the start date, but left between the two dates.
  - {{people}} who were added between the two dates and left again.
  
### Row Data
If you choose row data, Lamplight will add rows to your results table to show the information by this field. The options you have in the drop-down will depend on the fields in your database. For example, the table below shows the row data by 'gender'. 

![{{Waiting List}} {{Report}} Rows Gender](14.5.0a.png)


##### Tags
Reports

###### waiting module

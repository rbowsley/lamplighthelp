# 14.1.4  <i class="fa fa-chart-line"></i> {{Report}} Presentation

> Once you have added the filters for your {{report}}, you can play with the {{report}} presentation to show the data in different ways



When you create a new report, the 'Report presentation' tab is the last one in the row. 

![Report Presentation Tab](13.1.4a.png)

You can show your overall figures grouped by {{workarea}}, location or any of your profile custom fields. 

### Show Data for All Fields in Tab

You can choose to break down your results using a custom profile tab, with a separate table for each of the fields.  For instance, if you have a ‘Personal’ Tab that captures demographic data, you could select that. 

![Report Presentation Data for Fields in Tab](13.1.4b.png)

When you run the report, {{Lamplight}} will produce a table for each field in your 'Personal' tab. You can see below that we have results for 'Ethnicity', and 'Status'. 

![Report Presentation Data for Fields in Tab](13.1.4c.png)

### Row Data

The row and column data drop-down lists give you the chance to specify exactly what you want to see in your table.  When you specify row data and run the {{report}}, {{Lamplight}} will present the information split into rows by the field that you have chosen.

For example, if you choose to sort the rows by what field you would like to see represented in the rows of your table, For example, you could choose to show your results by 'Day of the week':

![{{Report}} Presented by Row Data](13.1.4d.png)

Then your table will look like this:

![Table Presented by Row Data](13.1.4e.png)

### Column Data

You can specify column data to show in the table in the same way. You can also use this to find more detail on your row data. 
This will create a single table.

 - You will need to clear other options from the presentation tab for this to work. 
 - If the ‘Show data for all fields in tabs’ has a selection, clear it by selecting ‘Select’ from the drop-down box. If you do not the {{report}} will continue to generate a table for each field value in the chosen tab.
 - You will need to choose one of the options from the 'Data to show' list (number of attendances or total length of {{work}} records, for example). This can't be 'All summary data', as this would cause {{Lamplight}} to ignore your choice of column data and populate the columns with the summary data instead.
 - In the example below the row data is '{{Subworkarea}}', while the column data is 'Day of the week'. We have chosen to show the number of different people.

![{{Report}} Presentation by Row and Column Data](13.1.4f.png)

The table then looks like this:

![Table Presented by Row and column Data](13.1.4g.png)

### Data to Show

As mentioned above, if you are specifying the column data that you want to see in the {{report}} table then you will need to choose one of the options for the data you want in the table. 

- Number of attendances. This is like ticks in a register or bums on seats. It gives you the number of times that people turned up to sessions.
- Number of different people. These are your unique individuals. You may have 20 attendances, but that is because 5 people turned up four times each. So your number of different people would be five.
- Number of sessions. Each {{activity}} record you save counts as a 'session'. This column gives you the total number that relate to the filters you have chosen.
- Total length of {{work}} records. If you ran your sessions continuously one after the other, this is how long they would last for.
- People hours delivered. Adding the total amount of time all these people spent attending sessions gives you your people hours.
- Number of {{work}} records.

You may see some more options here - these relate to custom fields that you have in your records.


###### core module


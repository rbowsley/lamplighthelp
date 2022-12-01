# 32.3.6 Types of Map: Multi Option Map

> A Multi Option map can be used when a data cell can include multiple values in one cell.  Sometimes this maybe because the data is a multi-select field (e.g. 'Languages spoken'), at other times because the data is combined into a single cell (e.g. attendance roles).  The data in the cell will be split up and translated one part at a time.  So "English, Spanish" might become "EN, SPA", for example.

To create a Multi Option Map, choose a select-type field from the selector, and click the 
'Multi Option Map' button.

After setting the column header, you will see a list of the options available, and text boxes for the replacement value
for each.  These are initially filled in with the same text.  Go through and enter the replacement values for each option.  
If you leave these blank, then the blank value will replace the data there.

**These maps are not directly linked to the original options.**  That means that if you change the text of your options, you
will need to update the CodeSet too to reflect the new source data option text.


### How it works 

When you view multi-select type data in tables, it's displayed as a comma separated list (e.g. "Engligh, Sylheti").
When you use this type of map in a CodeSet, it will take the value in the table and split it into chunks at each comma,
and map each part individually.  It will then combine the translated parts into a single comma separated string.

For example, let's say your Map translates "English" to "01" and "Sylheti" to "02".

Someone who spoke both would show "English, Sylheti" in a data table.

The Map takes this and splits it into two: "English" and then "Sylheti".

It transforms "English" to "01", and then "Sylheti" to "02".

And then it combines them into a single value "01, 02" which is displayed as the final data.


### Commas in option text 

All of that means that you should avoid using commas in the text of your options within your main system.  You should change
the text of the option in system admin before creating the Multi Option Map.


###### codeset module
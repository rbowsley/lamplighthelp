# 32.3.4 Types of Map: Numeric Range Map

> Numeric fields can be mapped to ranges: age bands are the most frequent use of this.  As a simple example, your Map can take any
> values 0 to 15 and output "child", and 16 - 100 "adult".  You can have as many bands as you need.

Numeric range maps are only available for number fields, including the age column calculated from a date of birth.  
To set a column to be an Numeric Range Map, select a numeric type field from the dropdown and click the 
'numeric range map' button.

You can then alter the column header, and enter the details of the first range you want in the map.  For example,
you might want values 0 up to (but not including) 5 mapped to 'Low'.  Note that the ranges include the lower value 
but not the upper value, so you would enter 0 , 5, and 'Low' to create your first range.

Save the Map, and you will return to the main CodeSet page.  You'll see your map, and a button to add further ranges.
Click this button and create the next range.  Let's say 5 up to (but not including) 10 is 'Medium', so enter 5, 10 and 'Medium'.
Save the range.

You can now repeat this to add further bandings.

This map works well for ages, mapping age into age bands.

There is some special behaviour for date of birth fields.  If you select the (date) option in the field selector, 
you will be able to create a Date Format Map for it.  If you select the (age) option you could create a Numeric Range
map (to get age bands). When you then come to use the CodeSet with a data view, the other date-of-birth columns
that are not in the map will be removed from the table.  In other words, you can only have a single date-of-birth
Value Map in a single CodeSet.

###### codeset module
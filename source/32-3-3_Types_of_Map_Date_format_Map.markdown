# 32.3.3 Types of Map: Date Format Data Map

> Date format maps re-format date fields in the way that you select, so that 28/07/2022 could become '2022-07-28' or '28th July 2022' or simply 'July'.

Date format maps are only available for date fields.  To set a column to be an Original Data Value Map, 
select a date type field from the dropdown and click the 'date format map' button.

You can then alter the column header, and select the format you want to use from the options provided.  Examples of each
date format are shown for the date today.

There is some special behaviour for date of birth fields.  If you select the (date) option in the field selector, 
you will be able to create a Date Format Map for it.  If you select the (age) option you could create a Numeric Range
map (to get age bands). When you then come to use the CodeSet with a data view, the other date-of-birth columns
that are not in the map will be removed from the table.  In other words, you can only have a single date-of-birth
Value Map in a single CodeSet.

###### codeset module
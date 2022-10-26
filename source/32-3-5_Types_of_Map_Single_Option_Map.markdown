# 32.3.5 Types of Map: Single Option Map

> A single option map will switch drop-down type fields, such as a typical gender field, or {{workarea}}.  You specify what each option available should be translated to.

Single Option fields are appropriate when you have a drop-down or tickbox style input for the source data, so that you
know the data is limited to a fixed set of possible values.  They should also be used when you know that the data you
will be using the CodeSet with presents the options as single values.

For example, a gender field in a profile is typically a drop-down field from which you can select a single option.
When you view this with a {{group}} and a data view, you'll see each client and their gender.  Each client can only have
a single value in this field.

This is a good place to use a Single Option Map.  To create the Map, select the field from the drop-down and select 
the 'Single Option Map' button.

After setting the column header, you will see a list of the options available, and text boxes for the replacement value
for each.  These are initially filled in with the same text.  Go through and enter the replacement values for each option.  
If you leave these blank, then the blank value will replace the data there.

**These maps are not directly linked to the original options.**  That means that if you change the text of your options, you
will need to update the CodeSet too to reflect the new source data option text.

Single Option maps are not appropriate when the data in your table has collated values, or for multi-select fields where 
one row can contain multiple values in a comma-separated list.  For example, a 'Languages spoken' field might have data
like 'English, Sylheti'.  A Single Option map looks at the combined value ('English, Sylheti') but because these are 
separate options in your system, it will not match them.  For these you will need to use a Multi Option Map.


###### codeset module
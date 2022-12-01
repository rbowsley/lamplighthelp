# 32.5.0 Using Report CodeSets with {{Group}}s and Data Views.

> Use a CodeSet with a {{group}} and {{group}} data view to transform the source data to your required output.  Go to {{Group}}s > View > {{group}} - data views {{report}} on the main menu.

Once you have created a CodeSet you can start to use it with a {{group}} and {{group}} data view to change the 
data output.  Go to {{Group}}s > View > {{group}} - data views {{report}} on the main menu. and select the
{{group}}, data view, and CodeSet to use:


Click run report to see the results.

You will see your 'translated' table with the CodeSet data shown.

We recommend that you use this as you are creating your CodeSet, and regularly re-run the {{report}} to check your
progress.  If you are doing this, we'd suggest you use a manual {{group}} with enough profiles in it to see the different
options and check everything is working as you need.

As usual tables can be downloaded.  Do be careful if you open downloads in Excel, however.  Excel will change your data,
for example by changing dates from the text format you've specified to and Excel date, or by removing leading '0's from 
numbers which can break codings.  If you do need to view your downloaded data, a text editor (like Notepad) won't
create these problems.

If you need to run this {{report}} regularly, we recommend you create a template and consider locking the {{group}} definition
and data view definition to maintain consistency.


###### codeset module
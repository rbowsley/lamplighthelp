# 32.3.7 Types of Map: Text Search Map

> A text search map can look for a particular set of phrases, and if it finds it will replace the data in the cell.
For example, a text search map could look for the word 'happy' in the data and just display '+1' if it finds it;
and then look for 'sad' in the data, and just display '-1'.  This can be useful for attendance  types amongst others.

Text search maps are available for most types of field.  Choose the field from the selector and click 'Text search map'.

First set the column header, and then create your first text match criteria.  Your Map can include several criteria,
and Lamplight will use the first one that matches to replace your data, so you may need to think about the order
that you enter them.

For example, you may need to map attendance in an {{activity}} table to a set of codes.  To simplify, let's say you
need to map "Client attended" to "01", "Client attended late" to "02", and "Client did not attend" to "03".

In the {{activity}} table, attendances are collated, so you may see something like "Client attended, "Staff attended" 
in a single data cell.  That means that your text searcher needs to look for your criteria text anywhere in the 
data.

Your first text search should be "Client attended late".  You need to select 'value contains text' in the 'How to match text'
field.  And the new value should be "02".

This one needs to be first, because the phrase "Client attended" appears in two of your attendance types.  If you started
with that, then it would match "Client attended" but also "Client attended late", and either would be translated to "01".

Once you save your Map and the first criteria, you can add more.  Find the Map in the CodeSet page (it will be at the 
bottom, they are listed in the order they are created) and click 'Add another text search'.

This time, enter "Client attended", "value contains text" and "02" and save this search.  And finally repeat for the 
"did not attend" option.

The searches will be carried out in the order they are listed, so make sure that you plan them out first.


###### codeset module
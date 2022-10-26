# 32.4.0 Techniques and Tips for Creating CodeSets 

> Report CodeSets are used in situations where you have to produce complex reports in a very particular format. One significant use is in MHS DS reporting to the NHS.  Here's what we've learned.


### Identify The Reports You Need

It sounds obvious, but make sure which reports you are going to need to submit, and make sure you have the up-to-date
definitions to hand.  There are multiple versions of MHS DS and it keeps getting updated, so ensure you are working
from the correct requirements.

### Where Is The Data Coming From?

For each report, figure out the primary source in Lamplight for the data you need.  What does each row in the output
represent?  In some cases each row is a person; in others it might be a {{referral}} or {{work}} record.

### Start With A Template

Now you know your starting point, create a simple template to get the raw data.  If your answer to the previous question
is a profile, create a data view that has the source columns you're going to need.  If it's {{activity}} records,
create an {{activity}} view template that has the additional columns you're going to need.

Don't worry so much about  the filters at this stage - you might want a smaller or simpler set of data while you're working
so that it runs faster.  For example you might want to use a manual {{group}} with say 20 profiles in it, rather than
the auto {{group}} you will likely need in the end.

You may need to add blank columns to your data view for some fields that will either be blank in the final output,
or have a constant value, but which are required for a valid output.

### Check It

Run the template you just created.  Go through the requirements you have.  Can you see where the data for each column
is going to come from in the template you have?

If there are gaps, you will need to figure out how to fill them.  Consider the options:

 - fill it in manually afterwards (easy now, painful later)
 - change your template to include the missing fields (great if they exist)
 - is the data in Lamplight at all? If not, do you need to create a new custom field somewhere? Make sure it's going to be possible to add it to your template when you've added it.
 - If the data is there, is there a way to bring it into the template you're using?

Some of the solutions to these questions can involve some really advanced use of Lamplight features, so if you're unsure
at this point you may want to contact us.

### Start Your CodeSet

Now that you are confident that you hvae the raw data in a template, start creating the CodeSet.  It's likely that each
output / report will require it's own CodeSet, so make sure the name you give and the description reflects this. We also
recommend that you include the version of the specification you are working to, and possibly the template you've created
that it will be used with.  You-in-the-future, or your colleagues, will thank you for adding plenty to the description now.

### Work Through The Columns

Work through the required output columns, creating a Data Map for each. Make sure the new column header is correct, 
down to the capitalisation - it's all case sensitive when you submit your data.

A few specific tips:
 - Dates generally have to be in dd-mm-yyyy format
 - Contact Method (ConsMediumUsed) may be a custom {{work}} record field
 - Attendance types likely need a Text Search map, using 'value contains text', to get the desired output

As you create each Map, run the template using your CodeSet to check it's doing what you expect and need.  You may
wish to have two tabs open, one with the CodeSet and one with the report (but keep both active or you'll end up 
being logged out by the other tab).



######### codeset module
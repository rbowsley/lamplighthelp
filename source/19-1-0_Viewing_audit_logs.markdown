# 19.1.0 Viewing audit logs

> Audit logs show what's happened in your system. To view audit logs, go to system administration > view audit logs.

You’ll see the most recent actions, when they happened, which member of staff carried it out, and the subject and if
relevant ID of the affected record. You can search these logs in the usual way – click ‘filter’. You can search by

 - when the action happened
 - the types of record or action involved
 - the system operator that carried out the action
 - ID of a particular record

As usual this table can be sorted by clicking on the column header, and downloaded as a csv file for further analysis in
Excel.

The table also contains two hidden columns. The 'details' column holds information about the data involved. This will vary
depending on the action. For example, if you save a record the details will be the data that was saved. If you view a
list of records the details will show you the IDs of the records viewed. Some records will show more technical
information about the data. This data is shown as the raw data.

The Request Details column shows information about the web request received. This shows:

 - the IP address of the operator,
 - the identifier of the web browser,
 - the cookie value,
 - the time of the request
 - the original URI of the request

This information is useful in troubleshooting scenarios, where this information can help diagnose issues. The IP address
can also help if you need to know where someone is accessing Lamplight from.

In some cases the ID column is a clickable link which you can click to see the current state of the record in question. 


##### Tags
System admin
Security


###### audit module
 
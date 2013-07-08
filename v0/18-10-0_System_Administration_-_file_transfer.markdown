# 18.10.0    System Administration - file transfer

> You can request backups of your database, and upload data into {{Lamplight}}. 

You can request backups of your database, which will be created and made available for download within an hour. Go to the admin menu and the File Transfer section. Please be aware that if you download your data you must ensure it is encrypted and saved securely: if in doubt, please don't download, or seek advice first.

![File transfer]({{imgpath}}158a.png)

The File Transfer section in the admin menu also allows uploads to be done into your system. If you have asked {{Lamplight}} to migrate data for you, you will need to send us the files securely via the **Send {{Lamplight}} a file securely** section. Upon receiving these files we will provide a quote for the time it will take us to migrate these files into {{Lamplight}} before we start any work. Alternatively you also have the option to do your own data migration via the **Upload profile data into your system**.

**Upload profile data from other systems**

To upload profile information about {{people}}, you need to export the data as a spreadsheet from your existing system. You can upload as much or as little data as you like: at a minimum, a name. You will then need to make sure it will be recognised by {{Lamplight}}. To do this:

  1. Save the file as a csv (comma separated variables) file
  2. Make sure the first row has headers (e.g. 'name', 'postcode' etc). You need to make sure that these headers will be recognised by {{Lamplight}}. {{Lamplight}} will not be able to import data it doesn't recognise, and it uses the column headers to work out where data should go. However it doesn't matter what order the columns are in. You can include data for custom fields you have added: you will need to make sure that the text of the row headers (and any options) match those set up in {{Lamplight}} exactly. If you have multi-select fields, separate each option with a semi-colon (;). You will not be able to upload linked fields (that appear as tables in the tabs), or {{work}} etc data - please contact us about data migration if you need to do this. 
 3. If your existing system has an automatically generated ID for each {{person}}, you can include this in your upload. If you do this, {{Lamplight}} will remember the ID, and if in the future you upload an updated spreadsheet with the same profile (from the same source, with the same IDs), {{Lamplight}} will update profiles, rather than creating new ones.

Once you have prepared your data, log in to {{Lamplight}} as an administrator, go to 'admin' and then 'system administration'. Click on 'Upload profile data into your system' in the 'File transfer' section. You will then see the screen below.
THISISANEW LINE![upload]({{imgpath}}158b.png)

You need to select a type of profile in the first section. You should then tell {{Lamplight}} the source of your data (e.g. Access, etc). 

The reason for doing this is that you may have several sources of data (i.e. different systems) that will have different IDs. {{Lamplight}} needs to know the source of the IDs so that it can use the correct IDs from the correct source to update profile information (see above). 

Finally, click on the 'choose file' button, select the csv file you've prepared, and click 'Open'. Then click 'upload file'.

If the upload was successful, you will receive a confirmation. If it wasn't, then your file was too big (over 1MB) or not a csv file. If you get the error {{message}} 'File could not be parsed properly', there's most likely a problem with the 'MIME' type - please see below for information on how to resolve this..

{{Lamplight}} looks at the headers in the spreadsheet, and the first few rows, and attempts to match them up to the fields in {{Lamplight}}, and shows you the results. Please check that the matching has worked OK.

![Upload3]({{imgpath}}158d. png)

If there were any problems matching the data, the fields will be listed below the table. You may need to go back and alter your spreadsheet to match up the fields. If you don't want to import the data, you can leave this part of {{Lamplight}} now - no data has been inserted into the system.

If you are happy to continue with the upload, you need to decide whether you want {{Lamplight}} to check and clean your data as it's inserted. If you do, it's likely that you'll get a list of errors after the data are inserted, where values in your spreadsheet were incorrect (e.g. invalid email addresses).

For your first upload **please do not select the final three options** on this screen. Whether you want your data validated is up to you: it may be a helpful way to clean up some of your data, but it's likely that you'll have to do some work on the data in your spreadsheet before you get a successful upload.

When you click the 'confirm' button, {{Lamplight}} will add the data from your spreadsheet into the system. This may take some time, depending on the size of your spreadsheet - although you could do more, we'd recommend uploading data in batches of up to 1000 records at a time. When it is complete, you will receive a confirmation.
 
![Upload4]({{imgpath}}158e.png)

If there were any errors, these will also be listed. Review these, and if you want to tidy up the data in your spreadsheet and re-upload, tick the 'Tick this checkbox to confirm you wish to undo this upload' and click 'undo'. This will delete all the data that have just been inserted into {{Lamplight}}. To ensure data integrity, **this is the only opportunity you have to undo the upload.**

**Appendix: File could not be parsed properly**

This error occurs when {{Lamplight}} cannot recognise that the file you've uploaded is a csv file. Files have additional information attached to them, including what type of file it is - this is separate to the filename. This means it is not enough for a file to be called (for example) mydatatoupload.csv - it actually needs to be a csv file, and be labelled as such.

Depending on your software and the way your system is set up, the csv file you've created may not be labelled in such a way that {{Lamplight}} can recognise it - the incorrect labels are added to the file. For security reasons we do not allow any kind of file to be uploaded, so you will need to carry out a couple of extra steps to get the upload to work.

These instructions apply to Windows: a similar approach will work on other platforms.

  1. Open up Notepad on your computer (perhaps Start > Programs or possibly Start > Programs > Accessories)
  2. Go to File > Open on the menu, and open the file you've prepared for upload to {{Lamplight}}. It should look something like this:
`'id','name','address1','web','primary purpose' '123','Argyle Homeless Shelter','123 Long Lane','www.lamplightdb.co.uk','Any/all' 'A456','Runway Employment {{Project}}','456 Test Road',,'Community centre'`

If it doesn't look a bit like this example, (and particularly if there's lots of squiggly characters), it's not a csv file at all. You need to go back to your spreadsheet package and make sure you 'Save as' csv. 

  3. In Notepad, click 'Save as' and make sure that the 'Save as type' dropdown says 'Text documents'. Give the file a new name and save it.

You should now be able to upload this new file (the notepad file) to {{Lamplight}}. 

[View the video](/help/video/id/43)
###### core module


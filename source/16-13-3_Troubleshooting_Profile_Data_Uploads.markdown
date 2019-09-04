# 16.13.3 Troubleshooting Profile Data Uploads

> If your import is not working, there are a number of simple checks you can make

If the upload is not working, you can check the following:

- All column names must exactly match field names in Lamplight. If a field has not been successfully matched, see if you can identify a difference between the column name in your spreadsheet and the field name in Lamplight.
- Open the .csv file using a basic text editor (such as Notepad in Windows or TextEdit on a Mac) and see what has been saved. This can help to identify a difference in the actual text of the file and what is being displayed in Excel.
- If date columns do not match or are different when viewing the .csv as plain text, click in the cell in Excel and check what it shows you. The cell format may need to be changed to 'Text' to avoid the date being formatted differently.
- Occasionally a translation in the system could affect the name used to import (for example, if ‘Last name’ in your system has been renamed to ‘Family name’). Check in Admin > System Administration > Customise Lamplight > change terms used in Lamplight for en_GB and use the original, untranslated terms.

If you are seeking to upload to existing profiles:
- Ensure that the profile ID numbers have been clearly matched to the correct profiles.
- Check that the selected profile type (e.g. {{person}}, {{org}} or {{family}}) and role (e.g. {{user}}, {{staff}} or {{volunteer}}) are the same as the type and role of the profiles to which you are uploading data.

### File Could Not Be Parsed Properly Error

This error occurs when Lamplight cannot recognise that the file you've uploaded is a csv file. Files have additional information attached to them, including what type of file it is - this is separate to the filename. This means it is not enough for a file to be called (for example) mydatatoupload.csv - it actually needs to be a csv file, and be labelled as such.

Depending on your software and the way your system is set up, the csv file you've created may not be labelled in such a way that Lamplight can recognise it - the incorrect labels are added to the file. For security reasons we do not allow any kind of file to be uploaded, so you will need to carry out a couple of extra steps to get the upload to work.

These instructions apply to Windows: a similar approach will work on other platforms:

- Open up Notepad on your computer (perhaps 'Start -> Programs' or possibly 'Start > Programs > Accessories'). 
- Go to 'File -> Open' on the menu, and open the file you've prepared for upload to Lamplight. It should look something like this:
   `'id','name','address1','web','primary purpose' '123','Argyle Homeless Shelter','123 Long Lane','www.lamplightdb.co.uk','Any/all' 'A456','Runway Employment Project','456 Test Road',,'Community centre'`.
- If it doesn't look a bit like this example, (and particularly if there's lots of squiggly characters), it's not a csv file at all. You need to go back to your spreadsheet package and make sure you 'Save as' csv.
- In Notepad, click 'Save as' and make sure that the 'Save as type' dropdown says 'Text documents'. Give the file a new name and save it.
- You should now be able to upload this new file (the notepad file) to Lamplight.


###### core module

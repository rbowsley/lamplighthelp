# 16.13.2 Uploading Prepared Profile Data

> When you have prepared your spreadsheet of profile data you can upload it into {{Lamplight}}

**It is strongly recommended to conduct a test first by uploading a duplicate file with just the first few rows of data.**

Profile data can only be uploaded by a database operator with System Administrator or Project Administrator access.

### Uploading Profile Information

- Click ‘admin’ in the main menu, then ‘system administration’.
- In the ‘File transfer’ section, click ‘Upload profile data into your system.’
- Choose the type and role of the profiles you are importing (e.g. 'person' and 'client'.)
- Give the ‘source’ of your data a name if you choose. This means that if you import often from the exact same format spreadsheet, your previous matching choices are saved for next time. If this is a second import of the same information, select the previous source.
- Click the ‘Browse…’ button and locate the .csv file to be uploaded.
- Click the ‘upload file’ button. 
- If the upload was successful you will receive confirmation. If it wasn't then your file was too big (over 1MB), or not a csv file. 
- On the next page will be displayed the fields Lamplight has been able to match, and to what they have been matched. Check these, scrolling right if needed.
- Any fields the system has not been able to match will also be displayed. Check these, correct your spreadsheet as necessary, and restart the upload.
 
![Matched Fields Upload Dialogue](16.13.2a.png)

- It is important that all the information is matched to a field. If importing to existing profiles, it is essential the profile ID numbers are correctly identified.

### Options

- Validating data: The system will ensure all the data has been checked before uploading, and list any records not imported due to invalid data.

The next three options are only relevant if you are adding data to existing profiles. If you are creating new profiles in the system then please ignore these.

- Duplicate data: This will check each name and address for duplicates.
- Titles and suffixes: Choose this and new titles and suffixes will be added to the lists of available ones (be cautious in case of typos).
- Overwrite existing records: If you select this, {{Lamplight}} matches the profile ID numbers in the .csv file to a profile in the system, and overwrites existing information (including blank information) with the new data.

### Upload

- Click ‘upload’. This may take some time, depending on the size of your spreadsheet. 
- When it is done you will be shown 'Upload results'. 
- At this point it is recommended that you leave {{Lamplight}} open on this tab and open a second browser tab to check the data in some of the profiles where information has been added or changed to see that it looks as you would expect. 
- If there is a problem with the upload, return to {{Lamplight}} in the orignal browser window and click the ‘Undo’ button to remove the imported data. **Once this tab has been closed, the upload can no longer be undone.**
- Undoing the upload will allow you to edit your spreadsheet and then upload again.
- If you are happy with the results of the upload then you can close the tab.


###### core module

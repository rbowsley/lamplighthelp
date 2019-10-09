# 16.13.2 <i class="fas fa-exchange-alt"></i> Uploading Prepared Profile Data

> When you have prepared your spreadsheet of profile data you can upload it into {{Lamplight}}



**We strongly recommend that you conduct a test first by uploading a duplicate file with just the first few rows of data.**  

Profile data can only be uploaded by a database operator with System Administrator or Project Administrator access.

### Uploading Profile Information

Uploading information is a two-step process: in the first step you upload the file and {{Lamplight}} matches headers and shows you what it's going to do; in the second step the data is actually imported.  You can safely carry out the first step without any records being created in {{Lamplight}}.

To upload prepared profile data in a .csv file:

- Click ‘admin’ in the main menu, then ‘system administration’.
- In the ‘File transfer’ section, click ‘Upload profile data into your system.’
- Choose the type and role of the profiles you are importing (e.g. 'person' and 'client'.)
- Give the ‘source’ of your data a name if you choose. This means that if you import often from the exact same format spreadsheet, your previous matching choices are saved for next time. If this is a second import of the same information, select the previous source.  If you are including IDs from your previous system and want to upload data you **must** select the source; if this is the first upload enter the source.
- Click the ‘Browse…’ button and locate the .csv file to be uploaded.
- Click the ‘upload file’ button. 

If the upload was successful you will receive confirmation. If it wasn't then your file was too big (over 1MB), or not a csv file. 

On the next page {{Lamplight}} will show you the fields it's been able to match and to what they have been matched. Check these, scrolling right if needed.  Any fields the system has not been able to match will also be displayed. Check these, correct your spreadsheet as necessary, and restart the upload.
 
![Matched Fields Upload Dialogue](16.13.2a.png)

It is important that all the information is matched to a field. If importing to existing profiles, it is essential the profile ID numbers are correctly identified.

### Options

#### Validating data 

The system will ensure all the data has been checked before uploading and list any records not imported due to invalid data.  This checks things like mobile phone numbers are valid.  We don't actually recommend using this: it's better to check your data carefully first.

#### Duplicate data

This will check each name and address for duplicates and skip them if any are found.  As this is non-interactive, we recommend not using this in general, unless you think there are high numbers of duplicates.

#### Titles and suffixes 

Choose this and new titles and suffixes will be added to the lists of available ones (be cautious in case of typos).  Again, it's better to set up the system with the titles and suffixes you need and make sure your data matches these.

#### Overwrite existing records

You can update existing records, instead of creating new ones, using the ID to match from.  There are two ways this can be done if you tick this checkbox:

#### Update using external system IDs

If you chose or entered a source of data on the previous screen, then {{Lamplight}} will check if this [source]-[ID] pair has been uploaded previously, and if so it will update the {{Lamplight}} profile with this data.  If the [source]-[ID] pair is not found, it will create a new profile and store the connection.  This means that you can upload data from multiple sources and any updates later will update {{Lamplight}}, rather than creating duplicates.

#### Update using {{Lamplight}} profile ID

If you did not select or enter a data source in the previous step, then {{Lamplight}} will treat an ID column in your data file as the {{Lamplight}} profile ID and update it if it exists.


In either case you will **overwrite your data in {{Lamplight}}** if you use this option; so be careful.  You will not be able to undo this if you make a mistake here.


### Upload

- Click ‘upload’. This may take some time, depending on the size of your spreadsheet. Please be patient!

When it is done you will be shown 'Upload results'.  At this point it is recommended that you leave {{Lamplight}} open on this tab and open a second browser tab to check the data in some of the profiles where information has been added or changed to see that it looks as you would expect. 

If there is a problem with the upload, return to {{Lamplight}} in the original browser window and click the ‘Undo’ button to remove the imported data. **Once this tab has been closed, the upload can no longer be undone.** Undoing the upload will allow you to edit your spreadsheet and then upload again.

When you are happy with the results of the upload then you can close the tab.


###### core module

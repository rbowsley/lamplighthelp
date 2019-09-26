# 16.15.0 <i class="fas fa-exchange-alt"></i> Backups

> You can request a complete backup of your system. If you do this you will need to think about saving the file securely, and any necessary encryption


You can request backups of your database at any time. They will be created in MySQL format and available for download within an hour. If you download your data you must ensure that it is encrypted and saved securely: if in doubt please do not download, or seek advice first. 


To request a download:

- Go to system admin.
- Find the 'File Transfer' section, and click on 'Request a backup for download'.

![Request a Backup for Download](16.15.0a.png)


The file will be ready in a couple of hours. 

To view a list or download backups, 

- Go to system admin.
- Find the 'File Transfer' section, and click on 'View recent backups'.
- Here you will see a list of available backups. Click the one that you would like to download. 



These backups are a complete snapshot of your database.  You cannot open them to read data easily: they will need to be imported into a MySQL compatible database server, and then you will need to run SQL queries to see data.  You can use these files to be sure you have your own backup, if that's what your risk assessment deems necessary.  You could also use them to migrate your data to a new system.  If you want to download data that you can view in Excel, you will be better served finding the data in {{Lamplight}} and downloading the tables you need.

###### core module

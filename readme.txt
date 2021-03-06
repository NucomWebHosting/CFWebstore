
To use CFWebstore for your whole site, upload the directory structure to your web root. If you prefer to run it as a separate application only, create a subdirectory and upload the files there. Be sure to keep the same directory structure (and file case on Unix). The 'cfwebstore.pdf' file in the documentation directory will give you complete directions on installing and using the software. 

The following directories are not necessary to upload: the documentation directory (user manual, license, and other informational files), database (database files and scripts) and the update directory (used for version 5 upgrades). If using the Access database, upload the file outside your webroot for better security, and if running a version 5 upgrade, upload the update directory, perform the upgrade, and then remove it. 

If you are upgrading from a previous version you'll need to run the appropriate upgrade scripts against your database. You can find the correct script in the /updates folder. 
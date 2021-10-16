# I thought of doing a public rep for the .exe so its easier!

Running BackupRestore.exe with -h, "BackupRestore.exe -h" on CMD will give you the following guide to running
<br>
`BioStar2 Backup & Restore -p <PortNumber> -k <KeyFile> -c <CertFile> -a <IP Address> -r <Resource Folder Location>`
<br><br>
An example of the proper running ettiquete is below:<br>
`BackupRestore.exe -p 449 -a 127.0.0.1 -k "C:\\biostar_cert.key" -c "C:\\biostar_cert.crt" -r "C:\\PythonTool\\BioStar2PythonBackupTool\\res"`
<br><br>
You have to define the resource folder when running the utility (During testing, when ran as admin (As needed for restore)
<br>
There were problems, as the utility kept going to tempfiles instead of the res. Just define it before running and it will be fine!
<br><br>
The download link for the backup will only work if site is secure (Or changed chrome settings)
<br>
Install the certificate properly first!
<br><br>
The tool by default is setup for 64 bit usage, but the folders used for backup can be changed within the settings section
<br>
The mysqldump.exe and mysql.exe instances can also be changed but use the default ones in the BioStar2 (x64) folder. 
<br><br>
Included cert files are for my specific installation, replace path in running above or actual files with your own BioStar2 ones. From (nginx\conf).
<br><br>
Its still rough, but any ideas, shoot me an email at gcartlidge@supremainc.com :)

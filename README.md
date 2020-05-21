# Download-Attach-Mail
This project automates the file downloads and mailing feature using python version 3.7.4.

Inputs Required: Sender's email, Receiver's email, Sender's Password, File Download URL

Libraries used: smtplib, email, requests 

# Instructions to run code:
1. Replace the Sender's Mail, Password, Receiver's Mail and download directory.
download path should be written as 
PATH_TO/DOWNLOAD_DIRECTORY/FILE_TO_WRITE_IN.FILE_EXTENSION
2. In sender's google account, disable 2 step verification and allow access to less secure apps.
3. In Windows Powershell, go to the autopy directory. (directory where folder is present)
4. Activate virtual environment by typing
. .\venv\Scripts\activate
5. run downmail.py as
python downmail.py

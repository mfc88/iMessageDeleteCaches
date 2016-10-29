# iMessageDeleteCaches
An automated script that deletes some iMessage Cache and Preferences files/folders.

Introduction

iMessageDeleteCaches is a simple bash script that removes iMessage files and folders stored within a user's "Library" folder 

Simply unzip the folder iMessageDeleteCaches_v1.0.0.zip to your Desktop, open a Terminal window, and drag and drop the file "iMessageDeleteCaches_v1.0.0" into the Terminal window and hit the Return key.

You'll be greeted with:
```
"Delete iMessage related files in Caches and Preferences? (y/n)
```
Type "y" or "Y" without quotes and the following folders/files will be deleted:
```
Folders in {user}/Library/Caches:
1.) com.apple.iCloudHelper 
2.) com.apple.imfoundation.IMRemoteURLConnectionAgent 
3.) com.apple.Messages

Files in {user}/Library/Preferences:
1.) com.apple.iChat* 
2.) com.apple.icloud* 
3.) com.apple.ids.service* 
4.) com.apple.imagent* 
5.) com.apple.imessage* 
6.) com.apple.imservice*

Folder and files in {user}/Library/Messages
1.) Archive
2.) chat.db
3.) chat.db-shm
4.) chat.db-wal
```

Then you'll be greeted with:
```
All done!
Do you want to reboot now? (y/n)
```
Type "y" or "Y" without quotes to reboot your computer (you may need to enter your admin password to continue).
Otheriwse, you can type "n" or "N" to abort the script and restart manually.


*Note: If you type an invalid character, then that will abort the script!

# win10debloater

This is a fork of Chris Titus Tech's (CTT) win10script repo.   
I have and will be making some modifications for my own use.  Please read before using. Changes you make using this script can be reversed
since it creates a Windows restore point. 

This is the Ultimate Windows 10 Debloater Script from a creation of multiple debloat scripts and gists from github. 

## CTT Additions

- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
Enjoy!

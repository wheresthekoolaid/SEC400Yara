# SEC400Yara
Final Class Project for Duane
--------------------------------------------------------------
Goals:
Create a yara rules that can be used to find and list file locations that have CC and SSNums

Create a user friendly Gui for administrators, this will be done from a linux system.

Linux System access is easy assume can use SSH to remote systems:
Windows use winexe to get powershell session:
Acquires all parameters from the user in bash script.

Git Structure:

EasyWinExe_Install - **Legacy Archive** Developer Notes

Linux_SED_Conf - **Legacy Archive** Sanatize output during Scan

PowerShell_Yara_Download - PowerShell Script that Downloads Yara, the Rules, then Runs the Scanner Saving Output to Log.

Run_Yara_Windows - **Legacy Archive** Was Onliner to run Yara for Windows

Windows_Yara_Scheduler - Powershell Script to Download Yara and Prep for Scheduled Task.

YaraRule_SSN_CC - Yara Rules in file format to be called and downloaded.

Yara_DropFile - PowerShell Script that Downloads Yara, the Rules, then Runs the Scanner Saving Output to Log.

Yara_Run_Gui - Bash Script--Command Controller--

Dependencies:
Linux:
Yara
bash
SSH
Winexe

Windows:
Powershell
Network Sharing
LaxerFirewall Rules


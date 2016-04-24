# SEC400Yara
Final Class Project for Duane
--------------------------------------------------------------
Goals:
Create a yara rules that can be used to find and list file locations that have CC and SSNums

Create a user friendly Gui for administrators, this will be done from a linux system.

Linux System access is easy assume can use SSH to remote systems:
Windows use winexe to get powershell session:
Acquires all parameters from the user in bash script.

Dependencies:
Linux:
Yara
Winexe

Windows:
Should all be called from linux gui


Future notes:
Use this as a sudo sed in windows
Credit: https://blogs.msdn.microsoft.com/zainnab/2007/07/08/grep-and-sed-with-powershell/

%{$_ -replace “expression”,”replace”}


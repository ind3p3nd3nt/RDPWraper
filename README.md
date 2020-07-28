# RDPWraper
Easy and automatic termsrv.dll patcher for Windows 10 1909 version 18363.959 - with updated ini file. To install First make an exception in Windows Defender and your antivirus for the executables and dll (IT WILL PICK IT UP) then make a "RDP Wrapper" directory in Program Files, Copy all those files inside then disconnect internet and in Command Prompt window execute "RDPWinst.exe -i"

### The goal of this project is to enable Remote Desktop Host support and concurrent RDP sessions on reduced functionality systems for home usage.

RDP Wrapper works as a layer between Service Control Manager and Terminal Services, so the original termsrv.dll file remains untouched. Also this method is very strong against Windows Update.

# Executables were taken from https://github.com/stascorp/rdpwrap and were in no case altered / modified: you can verify yourself, I am not trying to infect you.

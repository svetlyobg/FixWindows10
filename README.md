# FixWindows10
 
## Windows 10 Search Showing "Blank Box" Fix

You need to open run box. Right click start button and hit RUN. Then type REGEDIT. Now navigate to: HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search
Make sure these are set to 0
CortanaConsent = dword 0
BingSearchEnabled = dword 0

To create BingSearchEnabled. Right click on Search and select New and then DWORD (32-bit) Value and name it BingSearchEnabled and set it to 0
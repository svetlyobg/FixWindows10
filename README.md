# FixWindows10
 
## Windows 10 Search Showing "Blank Box" Fix

RUN -> REGEDIT

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search

CortanaConsent = dword 0
BingSearchEnabled = dword 0

To create BingSearchEnabled. Right click on Search and select New and then DWORD (32-bit) Value and name it BingSearchEnabled and set it to 0
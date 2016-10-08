# InstallWinOnExternal

1. dism /apply-image /imagefile=j:\sources\install.esd /index:1 /applydir:h:\
2. bcdboot h:\Windows /s h: /f ALL

j: -> drive letter windows sources install
h: -> drive letter External or USB (> 16GB)

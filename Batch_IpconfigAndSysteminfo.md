# Batch file สำหรับเช็ค IP Adress และ Systeminfo
~~~
@echo
set filename=%date:~10,4%%date:~7,2%%date:~4,2%_%time:~0,2%%time:~3,2%%time:~6,2%
C:\Windows\System32\ipconfig.exe /all >>%filename%_ip.txt
C:\Windows\System32\systeminfo.exe >> %filename%_name.txt
C:\Windows\System32\netstat.exe -nao | find "LIST" >> %filename%_Stat.txt
exit
~~~

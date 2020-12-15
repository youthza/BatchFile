# ใช้สำหรับค้นหา file ใน folder ทุก Directory และทำการ Backup
~~~
@echo off
set date=%date:~10,4%%date:~4,2%%date:~7,2%_%
forfiles /p "source path"/s /d -2 /c"cmd /c XCOPY @file destination path /e /s /i /y 
~~~

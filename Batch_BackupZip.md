# Backup โดยการทำในรูปแบบ .Zip
~~~
@echo off
set zone=%date:~10,4%%date:~4,2%%date:~7,2%
C:\7za.exe a SOURCE_PATH DESTINATION_PATH
~~~

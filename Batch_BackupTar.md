# Batch file ใช้สำหรับ Backup file ให้ออกมาในรูปแบบ .Tar 
## สามารถกำหนด path ที่จะ backup ได้มากกว่า 1 Source path
~~~
@echo
set zone=%date:~10,4%%date:~4,2%%date:~7,2%
7za.exe a -ttar destination_path  Source_path
~~~

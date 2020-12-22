# Batch file ใช้สำหรับ Backup file ให้ออกมาในรูปแบบ .Tar 
## สามารถกำหนด path ที่จะ backup ได้มากกว่า 1 Source path
## *จำเป็นต้องมีไฟล์ 7za.exe ด้วย*
~~~
@echo
set zone=%date:~10,4%%date:~4,2%%date:~7,2%
7za.exe a -ttar DESTINATION_PATH  SOURCE_PATH
~~~

# Batch file ใช้สำหรับ Remove file
~~~
forfiles /p "Path" /s /d -5 /c "cmd /c del @file : date >= 5 days >NUL"
~~~

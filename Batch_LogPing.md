# Batch file สำหรับเก็บ LogPing
~~~
@ECHO OFF
:LOOPSTART
ping 10.25.10.25 -t  >> filename.txt | findstr "request time out "
GOTO LOOPSTART
~~~

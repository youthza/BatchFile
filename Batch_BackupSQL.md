# BackupSQL 
~~~
set date=%date:~10,4%%date:~4,2%%date:~7,2%_%time:~0,2%%time:~3,2%%time:~6,2%
echo %date%
sqlcmd -S localhost -U USER -P PASSWORD -Q "BACKUP DATABASE DMS TO DISK ='Path %date%'"
~~~

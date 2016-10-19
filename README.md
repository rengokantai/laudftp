# laudftp
##1. Working with FTP
###1 What is FTP?
Active: server semds data  
Passive: client requests data, works better with NAT

###6 Connecting to FTP from the command line
####00:40
mac
```
ftp
open ke.com
```
####03:03
download
```
get filename
mget *   //download all files, does not download folders
```
toggle off prompt
```
prompt
```

####03:43
jump to command line
```
!
```
####04:19
delete
```
delete filename
```
###7 Exploring SFTP
####01:14
```
sftp user@ip
sftp -oPort=2222 user@ip
```
in case username with At sign
```
sftp -oUser=user@com ip
```
?->list of comand line

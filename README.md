mysqldumptos3
=============

Shell script to take the backup of mysql on s3 bucket

Before using this script, you must have to install and properly configure s3cmd.

On CentOS/RHEL/Fedora:
---------------------
```
yum install s3cmd
```
On Ubuntu/Dabian:
-----------------
```
$ apt-get install s3cmd
```
Configure s3cmd to work with your account

```
s3cmd --configure
```

Then change the desired parameters in the shell script.

Thanks

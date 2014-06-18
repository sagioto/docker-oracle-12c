docker-oracle-12c
=================

Dockerfile of Oracle Database 12c

This is based on [wnameless' project for oracle 11g](https://github.com/wnameless/docker-oracle-xe-11g)

I will try to integrate the steps described by M.el Khamlichi in [here](http://www.unixmen.com/install-oracle-database-12-oracle-linux-6-5/)
and the steps described by Oracle in [here](http://docs.oracle.com/cd/E16655_01/install.121/e17720/app_cloning.htm#LADBI7852)

Because of licenesing issues, you will have to get the dbhome_1.zip yourselves by zipping a pre-existing installation like so:
```shell
cd /
zip -r dbhome_1.zip /u01/app/oracle/product/12.1.0/dbhome_1
```

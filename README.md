# pure-ftp
how to install a pure-ftp server on centos 7

`yum install pure-ftp`

`useradd -g ftp sysadmin`

`mkdir /home/sysadmin/hub`

`pure-pw useradd admin -u sysadmin -g ftp -d /home/sysadmin/hub`

`pure-pw mkdb`

`systemctl restart pure-ftpd`

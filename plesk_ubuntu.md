## plesk php not found on command line
```bash
export PATH=/opt/plesk/php/7.3/bin/:$PATH
```
or add php path to /etc/profile
```
sudo su
echo "PATH=/opt/plesk/php/7.3/bin/:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin" >> /etc/profile
exit
```
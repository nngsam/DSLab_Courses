Hands-on Lab: Navigating and Managing Files and Directories

```
theia@theia-u11203041:/home/project$ pwd
/home/project
theia@theia-u11203041:/home/project$ ls
theia@theia-u11203041:/home/project$ ls /bin
bash          chgrp          false     lesspipe    nisdomainname  sh.distrib  which
bunzip2       chmod          fgrep     ln          pidof          sleep       ypdomainname
bzcat         chown          findmnt   login       ping           stty        zcat
bzcmp         cp             fuser     ls          ping6          su          zcmp
bzdiff        dash           grep      lsblk       ps             sync        zdiff
bzegrep       date           gunzip    mkdir       pwd            tar         zegrep
bzexe         dd             gzexe     mknod       rbash          tempfile    zfgrep
bzfgrep       df             gzip      mktemp      readlink       touch       zforce
bzgrep        dir            hostname  more        rm             true        zgrep
bzip2         dmesg          kill      mount       rmdir          umount      zless
bzip2recover  dnsdomainname  less      mountpoint  rnano          uname       zmore
bzless        domainname     lessecho  mv          run-parts      uncompress  znew
bzmore        echo           lessfile  nano        sed            vdir
cat           egrep          lesskey   netstat     sh             wdctl
theia@theia-u11203041:/home/project$ ls /bin/ls
/bin/ls
theia@theia-u11203041:/home/project$ ls /bin
bash          chgrp          false     lesspipe    nisdomainname  sh.distrib  which
bunzip2       chmod          fgrep     ln          pidof          sleep       ypdomainname
bzcat         chown          findmnt   login       ping           stty        zcat
bzcmp         cp             fuser     ls          ping6          su          zcmp
bzdiff        dash           grep      lsblk       ps             sync        zdiff
bzegrep       date           gunzip    mkdir       pwd            tar         zegrep
bzexe         dd             gzexe     mknod       rbash          tempfile    zfgrep
bzfgrep       df             gzip      mktemp      readlink       touch       zforce
bzgrep        dir            hostname  more        rm             true        zgrep
bzip2         dmesg          kill      mount       rmdir          umount      zless
bzip2recover  dnsdomainname  less      mountpoint  rnano          uname       zmore
bzless        domainname     lessecho  mv          run-parts      uncompress  znew
bzmore        echo           lessfile  nano        sed            vdir
cat           egrep          lesskey   netstat     sh             wdctl
theia@theia-u11203041:/home/project$ ls /bin/b*
/bin/bash     /bin/bzcmp    /bin/bzexe    /bin/bzip2         /bin/bzmore
/bin/bunzip2  /bin/bzdiff   /bin/bzfgrep  /bin/bzip2recover
/bin/bzcat    /bin/bzegrep  /bin/bzgrep   /bin/bzless
theia@theia-u11203041:/home/project$ ls /bin/*r
/bin/bzip2recover  /bin/dir  /bin/fuser  /bin/mkdir  /bin/rmdir  /bin/tar  /bin/vdir
theia@theia-u11203041:/home/project$ ls -l
total 0
theia@theia-u11203041:/home/project$ ls -la /etc
total 680
drwxr-xr-x 1 root     root      4096 Feb 27  2023 .
drwxr-xr-x 1 root     root      4096 Sep 16 04:25 ..
-rw-r--r-- 1 root     root      3028 Jan 26  2023 adduser.conf
drwxr-xr-x 1 root     root      4096 Feb 27  2023 alternatives
drwxr-xr-x 3 root     root      4096 Feb 27  2023 apparmor
drwxr-xr-x 1 root     root      4096 Feb 27  2023 apparmor.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 apt
-rw-r--r-- 1 root     root      2319 Feb 27  2023 bash.bashrc
drwxr-xr-x 2 root     root      4096 Feb 27  2023 bash_completion.d
-rw-r--r-- 1 root     root       367 Jan 27  2016 bindresvport.blacklist
drwxr-xr-x 3 root     root      4096 Feb 27  2023 ca-certificates
-rw-r--r-- 1 root     root      5432 Feb 27  2023 ca-certificates.conf
drwxr-xr-x 2 root     root      4096 Feb 27  2023 calendar
drwxr-xr-x 3 root     root      4096 Feb 27  2023 cassandra
drwxr-xr-x 2 root     root      4096 Jan 26  2023 cloud
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.daily
drwxr-xr-x 2 root     root      4096 Feb 27  2023 cron.hourly
drwxr-xr-x 2 root     root      4096 Feb 27  2023 cron.monthly
-rw-r--r-- 1 root     root       722 May 10  2022 crontab
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.weekly
drwxr-xr-x 4 root     root      4096 Feb 27  2023 dbus-1
-rw-r--r-- 1 root     root      2969 Feb 28  2018 debconf.conf
-rw-r--r-- 1 root     root        11 Jun 25  2017 debian_version
drwxr-xr-x 1 root     root      4096 Feb 27  2023 default
-rw-r--r-- 1 root     root       604 Aug 13  2017 deluser.conf
drwxr-xr-x 3 root     root      4096 Feb 27  2023 dhcp
drwxr-xr-x 2 root     root      4096 Oct 21  2021 docker
drwxr-xr-x 1 root     root      4096 Feb 27  2023 dpkg
drwxr-xr-x 3 root     root      4096 Feb 27  2023 emacs
-rw-r--r-- 1 root     root       106 Jan 26  2023 environment
drwxr-xr-x 4 root     root      4096 Feb 27  2023 fonts
-rw-r--r-- 1 root     root        37 Jan 26  2023 fstab
-rw-r--r-- 1 root     root      2584 Feb  1  2018 gai.conf
drwxr-xr-x 3 root     root      4096 Feb 27  2023 gdb
drwxr-xr-x 2 root     root      4096 Feb 27  2023 groff
drwxr-xr-x 2 root     root      4096 Feb 27  2023 groovy
-rw-r--r-- 1 root     root       606 Feb 27  2023 group
-rw-r--r-- 1 root     root       598 Feb 27  2023 group-
-rw-r----- 1 root     shadow     503 Feb 27  2023 gshadow
-rw-r----- 1 root     shadow     495 Feb 27  2023 gshadow-
drwxr-xr-x 3 root     root      4096 Feb 27  2023 gss
-rw-r--r-- 1 root     root        92 Apr  9  2018 host.conf
-rw-r--r-- 1 root     root        16 Sep 16 04:25 hostname
-rw-r--r-- 1 root     root       263 Sep 16 04:25 hosts
drwxr-xr-x 1 root     root      4096 Feb 27  2023 init.d
-rw-r--r-- 1 root     root      1748 May 15  2017 inputrc
-rw-r--r-- 1 root     root        26 Sep  6  2021 issue
-rw-r--r-- 1 root     root        19 Sep  6  2021 issue.net
drwxr-xr-x 3 root     root      4096 Feb 27  2023 java
drwxr-xr-x 3 root     root      4096 Feb 27  2023 .java
drwxr-xr-x 5 root     root      4096 Feb 27  2023 java-11-openjdk
drwxr-xr-x 5 root     root      4096 Feb 27  2023 java-8-openjdk
drwxr-xr-x 1 root     root      4096 Jan 26  2023 kernel
drwxr-xr-x 2 root     root      4096 Feb 27  2023 ldap
-rw-r--r-- 1 root     root     38873 Feb 27  2023 ld.so.cache
-rw-r--r-- 1 root     root        34 Jan 27  2016 ld.so.conf
drwxr-xr-x 1 root     root      4096 Feb 27  2023 ld.so.conf.d
-rw-r--r-- 1 root     root       267 Apr  9  2018 legal
-rw-r--r-- 1 root     root       191 Feb  7  2018 libaudit.conf
drwxr-xr-x 4 root     root      4096 Feb 27  2023 lighttpd
-rw-r--r-- 1 root     root      2995 May  3  2022 locale.alias
-rw-r--r-- 1 root     root      9397 Feb 27  2023 locale.gen
lrwxrwxrwx 1 root     root        36 Feb 27  2023 localtime -> /usr/share/zoneinfo/America/New_York
drwxr-xr-x 3 root     root      4096 Feb 27  2023 logcheck
-rw-r--r-- 1 root     root     10550 Jan 25  2018 login.defs
-rw-r--r-- 1 root     root       703 Aug 21  2017 logrotate.conf
drwxr-xr-x 1 root     root      4096 Feb 27  2023 logrotate.d
-rw-r--r-- 1 root     root       105 Sep  6  2021 lsb-release
-rw-r--r-- 1 root     root         0 Jan 26  2023 machine-id
-rw-r--r-- 1 root     root       111 May 12  2020 magic
-rw-r--r-- 1 root     root       111 May 12  2020 magic.mime
-rw-r--r-- 1 root     root      2621 Feb 27  2023 mailcap
-rw-r--r-- 1 root     root       449 Jul 15  2016 mailcap.order
-rw-r--r-- 1 root     root      5174 Aug  4  2018 manpath.config
-rw-r--r-- 1 root     root     24301 Jul 15  2016 mime.types
-rw-r--r-- 1 root     root       812 Mar 24  2018 mke2fs.conf
-rw-r--r-- 1 root     root      2154 Mar 22  2019 mongodb.conf
-rw-r--r-- 1 root     root      9048 Feb 13  2018 nanorc
drwxr-xr-x 2 root     root      4096 Dec 25  2016 network
drwxr-xr-x 3 root     root      4096 Feb 27  2023 NetworkManager
-rw-r--r-- 1 root     root        91 Apr  9  2018 networks
-rw-r--r-- 1 root     root       497 Oct  5  2016 nsswitch.conf
-rw-r--r-- 1 root     root      2517 Aug 17  2020 ntp.conf
drwxr-xr-x 2 root     root      4096 Jan 26  2023 opt
lrwxrwxrwx 1 root     root        21 Sep  6  2021 os-release -> ../usr/lib/os-release
-rw-r--r-- 1 root     root       552 Apr  4  2018 pam.conf
drwxr-xr-x 1 root     root      4096 Feb 27  2023 pam.d
-rw-r--r-- 1 root     root      1279 Feb 27  2023 passwd
-rw-r--r-- 1 root     root      1252 Feb 27  2023 passwd-
drwxr-xr-x 4 root     root      4096 Feb 27  2023 perl
drwxr-xr-x 1 root     root      4096 Feb 27  2023 php
drwxr-xr-x 3 root     root      4096 Feb 27  2023 pm
drwxr-xr-x 3 postgres postgres  4096 Feb 27  2023 postgresql
drwxr-xr-x 3 root     root      4096 Feb 27  2023 postgresql-common
-rw-r--r-- 1 root     root       581 Feb 27  2023 profile
drwxr-xr-x 1 root     root      4096 Feb 27  2023 profile.d
-rw-r--r-- 1 root     root      2932 Dec 25  2016 protocols
-rw------- 1 root     root         0 Jan 26  2023 .pwd.lock
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python2.7
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3.6
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3.8
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc0.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc1.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc2.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc3.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc4.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc5.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc6.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rcS.d
-rw-r--r-- 1 root     root       115 Sep 16 04:25 resolv.conf
-rwxr-xr-x 1 root     root       268 Jul 21  2017 rmt
-rw-r--r-- 1 root     root       887 Dec 25  2016 rpc
-rw-r--r-- 1 root     root      4141 Jan 25  2018 securetty
drwxr-xr-x 1 root     root      4096 Jan 26  2023 security
drwxr-xr-x 2 root     root      4096 Jan 26  2023 selinux
-rw-r--r-- 1 root     root     10368 Mar 31  2022 sensors3.conf
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sensors.d
-rw-r--r-- 1 root     root     19183 Dec 25  2016 services
-rw-r----- 1 root     shadow     675 Feb 27  2023 shadow
-rw-r----- 1 root     shadow     675 Feb 27  2023 shadow-
-rw-r--r-- 1 root     root        73 Jan 26  2023 shells
drwxr-xr-x 2 root     root      4096 Jan 26  2023 skel
drwxr-xr-x 2 root     root      4096 Feb 27  2023 ssh
drwxr-xr-x 1 root     root      4096 Feb 27  2023 ssl
-rw-r--r-- 1 root     root        19 Feb 27  2023 subgid
-rw-r--r-- 1 root     root         0 Jan 26  2023 subgid-
-rw-r--r-- 1 root     root        19 Feb 27  2023 subuid
-rw-r--r-- 1 root     root         0 Jan 26  2023 subuid-
-r--r----- 1 root     root       784 Feb 27  2023 sudoers
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sudoers.d
-rw-r--r-- 1 root     root      2683 Jan 17  2018 sysctl.conf
drwxr-xr-x 1 root     root      4096 Feb 27  2023 sysctl.d
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sysstat
drwxr-xr-x 1 root     root      4096 Oct 25  2017 systemd
drwxr-xr-x 2 root     root      4096 Jan 26  2023 terminfo
-rw-r--r-- 1 root     root        17 Feb 27  2023 timezone
-rw-r--r-- 1 root     root      1260 Feb 25  2018 ucf.conf
drwxr-xr-x 3 root     root      4096 Feb 27  2023 ufw
drwxr-xr-x 1 root     root      4096 Feb 27  2023 update-motd.d
-rw-r--r-- 1 root     root      4942 Apr  8  2019 wgetrc
drwxr-xr-x 1 root     root      4096 Feb 27  2023 X11
drwxr-xr-x 3 root     root      4096 Feb 27  2023 xdg
drwxr-xr-x 3 root     root      4096 Feb 27  2023 xml
theia@theia-u11203041:/home/project$ ls /etc
adduser.conf            fonts            locale.alias    perl               services
alternatives            fstab            locale.gen      php                shadow
apparmor                gai.conf         localtime       pm                 shadow-
apparmor.d              gdb              logcheck        postgresql         shells
apt                     groff            login.defs      postgresql-common  skel
bash.bashrc             groovy           logrotate.conf  profile            ssh
bash_completion.d       group            logrotate.d     profile.d          ssl
bindresvport.blacklist  group-           lsb-release     protocols          subgid
ca-certificates         gshadow          machine-id      python             subgid-
ca-certificates.conf    gshadow-         magic           python2.7          subuid
calendar                gss              magic.mime      python3            subuid-
cassandra               host.conf        mailcap         python3.6          sudoers
cloud                   hostname         mailcap.order   python3.8          sudoers.d
cron.d                  hosts            manpath.config  rc0.d              sysctl.conf
cron.daily              init.d           mime.types      rc1.d              sysctl.d
cron.hourly             inputrc          mke2fs.conf     rc2.d              sysstat
cron.monthly            issue            mongodb.conf    rc3.d              systemd
crontab                 issue.net        nanorc          rc4.d              terminfo
cron.weekly             java             network         rc5.d              timezone
dbus-1                  java-11-openjdk  NetworkManager  rc6.d              ucf.conf
debconf.conf            java-8-openjdk   networks        rcS.d              ufw
debian_version          kernel           nsswitch.conf   resolv.conf        update-motd.d
default                 ldap             ntp.conf        rmt                wgetrc
deluser.conf            ld.so.cache      opt             rpc                X11
dhcp                    ld.so.conf       os-release      securetty          xdg
docker                  ld.so.conf.d     pam.conf        security           xml
dpkg                    legal            pam.d           selinux
emacs                   libaudit.conf    passwd          sensors3.conf
environment             lighttpd         passwd-         sensors.d
theia@theia-u11203041:/home/project$ mkdir scripts
theia@theia-u11203041:/home/project$ ls
scripts
theia@theia-u11203041:/home/project$ cd scripts
theia@theia-u11203041:/home/project/scripts$ pwd
/home/project/scripts
theia@theia-u11203041:/home/project/scripts$ cd
theia@theia-u11203041:~$ pwd
/home/theia
theia@theia-u11203041:~$ cd ..
theia@theia-u11203041:/home$ cd
theia@theia-u11203041:~$ touch myfile.txt
theia@theia-u11203041:~$ ls
docker-compose         javasharedresources  package.json  skills-network-extension-v0.1.0.tgz
dsdriver               lib                  plugins       src-gen
entrypoint.sh          myfile.txt           postgres      webpack.config.js
gen-webpack.config.js  node_modules         README.md     yarn.lock
theia@theia-u11203041:~$ touch my file.txt
theia@theia-u11203041:~$ ls
docker-compose         lib           postgres
dsdriver               my            README.md
entrypoint.sh          myfile.txt    skills-network-extension-v0.1.0.tgz
file.txt               node_modules  src-gen
gen-webpack.config.js  package.json  webpack.config.js
javasharedresources    plugins       yarn.lock
theia@theia-u11203041:~$ touch myfile.txt
theia@theia-u11203041:~$ date -r myfile.txt
Sat Sep 16 04:39:34 EDT 2023
theia@theia-u11203041:~$ find /etc -name \'*.txt\'
find: ‘/etc/ssl/private’: Permission denied
theia@theia-u11203041:~$ re -i my file.txt
bash: re: command not found
theia@theia-u11203041:~$ rm -i my file.txt
rm: remove regular empty file 'my'?    
rm: remove regular empty file 'file.txt'?  
theia@theia-u11203041:~$ rm -i myfile.txt
rm: remove regular empty file 'myfile.txt'?  
theia@theia-u11203041:~$ rm -i myfile.txt
rm: remove regular empty file 'myfile.txt'? y
theia@theia-u11203041:~$ rm -i myfile.txt
rm: cannot remove 'myfile.txt': No such file or directory
theia@theia-u11203041:~$ re -i my file.txt
bash: re: command not found
theia@theia-u11203041:~$ y
bash: y: command not found
theia@theia-u11203041:~$ rm -i my file.txt
rm: remove regular empty file 'my'? y
rm: remove regular empty file 'file.txt'? y
theia@theia-u11203041:~$ ls
docker-compose         lib           README.md
dsdriver               node_modules  skills-network-extension-v0.1.0.tgz
entrypoint.sh          package.json  src-gen
gen-webpack.config.js  plugins       webpack.config.js
javasharedresources    postgres      yarn.lock
theia@theia-u11203041:~$ touch users.txt
theia@theia-u11203041:~$ mv users.txt user-info.txt
theia@theia-u11203041:~$ ls
docker-compose         node_modules                         src-gen
dsdriver               package.json                         user-info.txt
entrypoint.sh          plugins                              webpack.config.js
gen-webpack.config.js  postgres                             yarn.lock
javasharedresources    README.md
lib                    skills-network-extension-v0.1.0.tgz
theia@theia-u11203041:~$ mv user-info.txt /tmp
theia@theia-u11203041:~$ ls
docker-compose         lib           README.md
dsdriver               node_modules  skills-network-extension-v0.1.0.tgz
entrypoint.sh          package.json  src-gen
gen-webpack.config.js  plugins       webpack.config.js
javasharedresources    postgres      yarn.lock
theia@theia-u11203041:~$ ls -l /tmp
total 13412
drwxr-xr-x 2 theia theia     4096 Sep 16 04:25 de99a39d-2d70-461b-9847-9c0b43adafb9
drwxr-xr-x 2 theia theia     4096 Sep 16 04:25 github-remote
-rw-r--r-- 1 theia theia 13701452 Feb 27  2023 helm-v3.6.1-linux-amd64.tar.gz
drwxr-xr-x 2 root  root      4096 Feb 27  2023 hsperfdata_root
drwxr-xr-x 2 theia theia     4096 Sep 16 04:25 http-remote
drwxr-xr-x 2 theia theia     4096 Feb 27  2023 linux-amd64
drwxr-xr-x 2 theia theia     4096 Sep 16 04:25 theia_upload
-rw-r--r-- 1 theia theia        0 Sep 16 04:47 user-info.txt
srwxr-xr-x 1 theia theia        0 Sep 16 04:35 vscode-git-cf1816fa35.sock
drwxr-xr-x 2 theia theia     4096 Sep 16 04:25 yarn--1694852749157-0.8998342736223632
theia@theia-u11203041:~$ ls /user-info.txt
ls: cannot access '/user-info.txt': No such file or directory
theia@theia-u11203041:~$ ls /tmp/user-info.txt
/tmp/user-info.txt
theia@theia-u11203041:~$ find / -type f -name "user-info.txt"
find: ‘/etc/ssl/private’: Permission denied
find: ‘/var/log/unattended-upgrades’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/lib/postgresql/15/main’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/spool/cron/crontabs’: Permission denied
find: ‘/root’: Permission denied
/tmp/user-info.txt
find: ‘/proc/tty/driver’: Permission denied
find: ‘/proc/35/task/35/fd’: Permission denied
find: ‘/proc/35/task/35/fdinfo’: Permission denied
find: ‘/proc/35/task/35/ns’: Permission denied
find: ‘/proc/35/fd’: Permission denied
find: ‘/proc/35/map_files’: Permission denied
find: ‘/proc/35/fdinfo’: Permission denied
find: ‘/proc/35/ns’: Permission denied
theia@theia-u11203041:~$ cp /tmp/user-info.txt user-info.txt
theia@theia-u11203041:~$ ls
docker-compose         node_modules                         src-gen
dsdriver               package.json                         user-info.txt
entrypoint.sh          plugins                              webpack.config.js
gen-webpack.config.js  postgres                             yarn.lock
javasharedresources    README.md
lib                    skills-network-extension-v0.1.0.tgz
theia@theia-u11203041:~$ cp /etc/passwd users.txt
theia@theia-u11203041:~$ ls
docker-compose         lib           README.md                            webpack.config.js
dsdriver               node_modules  skills-network-extension-v0.1.0.tgz  yarn.lock
entrypoint.sh          package.json  src-gen
gen-webpack.config.js  plugins       user-info.txt
javasharedresources    postgres      users.txt
theia@theia-u11203041:~$ ls /home
project  theia
theia@theia-u11203041:~$ cd 
theia@theia-u11203041:~$ pwd
/home/theia
theia@theia-u11203041:~$ mkdir tmp
theia@theia-u11203041:~$ ls
docker-compose         lib           README.md                            users.txt
dsdriver               node_modules  skills-network-extension-v0.1.0.tgz  webpack.config.js
entrypoint.sh          package.json  src-gen                              yarn.lock
gen-webpack.config.js  plugins       tmp
javasharedresources    postgres      user-info.txt
theia@theia-u11203041:~$ cd tmp
theia@theia-u11203041:~/tmp$ touch display.sh
theia@theia-u11203041:~/tmp$ ls -l
total 0
-rw-r--r-- 1 theia theia 0 Sep 16 04:58 display.sh
theia@theia-u11203041:~/tmp$ cp display.sh report.sh
theia@theia-u11203041:~/tmp$ mv report.sh ../
theia@theia-u11203041:~/tmp$ ls
display.sh
theia@theia-u11203041:~/tmp$ ls ../
docker-compose         lib           README.md                            user-info.txt
dsdriver               node_modules  report.sh                            users.txt
entrypoint.sh          package.json  skills-network-extension-v0.1.0.tgz  webpack.config.js
gen-webpack.config.js  plugins       src-gen                              yarn.lock
javasharedresources    postgres      tmp
theia@theia-u11203041:~/tmp$ ls /report.sh
ls: cannot access '/report.sh': No such file or directory
theia@theia-u11203041:~/tmp$ ls ../report.sh
../report.sh
theia@theia-u11203041:~/tmp$ rm -i display.sh
rm: remove regular empty file 'display.sh'? y
theia@theia-u11203041:~/tmp$ ls -ltr /etc/
total 668
-rw-r--r-- 1 root     root        34 Jan 27  2016 ld.so.conf
-rw-r--r-- 1 root     root       367 Jan 27  2016 bindresvport.blacklist
-rw-r--r-- 1 root     root     24301 Jul 15  2016 mime.types
-rw-r--r-- 1 root     root       449 Jul 15  2016 mailcap.order
-rw-r--r-- 1 root     root       497 Oct  5  2016 nsswitch.conf
-rw-r--r-- 1 root     root     19183 Dec 25  2016 services
-rw-r--r-- 1 root     root       887 Dec 25  2016 rpc
-rw-r--r-- 1 root     root      2932 Dec 25  2016 protocols
drwxr-xr-x 2 root     root      4096 Dec 25  2016 network
-rw-r--r-- 1 root     root      1748 May 15  2017 inputrc
-rw-r--r-- 1 root     root        11 Jun 25  2017 debian_version
-rwxr-xr-x 1 root     root       268 Jul 21  2017 rmt
-rw-r--r-- 1 root     root       604 Aug 13  2017 deluser.conf
-rw-r--r-- 1 root     root       703 Aug 21  2017 logrotate.conf
drwxr-xr-x 1 root     root      4096 Oct 25  2017 systemd
-rw-r--r-- 1 root     root      2683 Jan 17  2018 sysctl.conf
-rw-r--r-- 1 root     root      4141 Jan 25  2018 securetty
-rw-r--r-- 1 root     root     10550 Jan 25  2018 login.defs
-rw-r--r-- 1 root     root      2584 Feb  1  2018 gai.conf
-rw-r--r-- 1 root     root       191 Feb  7  2018 libaudit.conf
-rw-r--r-- 1 root     root      9048 Feb 13  2018 nanorc
-rw-r--r-- 1 root     root      1260 Feb 25  2018 ucf.conf
-rw-r--r-- 1 root     root      2969 Feb 28  2018 debconf.conf
-rw-r--r-- 1 root     root       812 Mar 24  2018 mke2fs.conf
-rw-r--r-- 1 root     root       552 Apr  4  2018 pam.conf
-rw-r--r-- 1 root     root        91 Apr  9  2018 networks
-rw-r--r-- 1 root     root       267 Apr  9  2018 legal
-rw-r--r-- 1 root     root        92 Apr  9  2018 host.conf
-rw-r--r-- 1 root     root      5174 Aug  4  2018 manpath.config
-rw-r--r-- 1 root     root      2154 Mar 22  2019 mongodb.conf
-rw-r--r-- 1 root     root      4942 Apr  8  2019 wgetrc
-rw-r--r-- 1 root     root       111 May 12  2020 magic.mime
-rw-r--r-- 1 root     root       111 May 12  2020 magic
-rw-r--r-- 1 root     root      2517 Aug 17  2020 ntp.conf
lrwxrwxrwx 1 root     root        21 Sep  6  2021 os-release -> ../usr/lib/os-release
-rw-r--r-- 1 root     root       105 Sep  6  2021 lsb-release
-rw-r--r-- 1 root     root        19 Sep  6  2021 issue.net
-rw-r--r-- 1 root     root        26 Sep  6  2021 issue
drwxr-xr-x 2 root     root      4096 Oct 21  2021 docker
-rw-r--r-- 1 root     root     10368 Mar 31  2022 sensors3.conf
-rw-r--r-- 1 root     root      2995 May  3  2022 locale.alias
-rw-r--r-- 1 root     root       722 May 10  2022 crontab
drwxr-xr-x 2 root     root      4096 Jan 26  2023 opt
-rw-r--r-- 1 root     root        37 Jan 26  2023 fstab
-rw-r--r-- 1 root     root        73 Jan 26  2023 shells
-rw-r--r-- 1 root     root         0 Jan 26  2023 subuid-
-rw-r--r-- 1 root     root         0 Jan 26  2023 subgid-
drwxr-xr-x 1 root     root      4096 Jan 26  2023 kernel
-rw-r--r-- 1 root     root      3028 Jan 26  2023 adduser.conf
drwxr-xr-x 2 root     root      4096 Jan 26  2023 selinux
drwxr-xr-x 2 root     root      4096 Jan 26  2023 skel
drwxr-xr-x 2 root     root      4096 Jan 26  2023 terminfo
drwxr-xr-x 1 root     root      4096 Jan 26  2023 security
-rw-r--r-- 1 root     root       106 Jan 26  2023 environment
-rw-r--r-- 1 root     root         0 Jan 26  2023 machine-id
drwxr-xr-x 2 root     root      4096 Jan 26  2023 cloud
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3.6
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python2.7
drwxr-xr-x 4 root     root      4096 Feb 27  2023 perl
drwxr-xr-x 3 root     root      4096 Feb 27  2023 ca-certificates
drwxr-xr-x 4 root     root      4096 Feb 27  2023 dbus-1
drwxr-xr-x 3 root     root      4096 Feb 27  2023 gss
drwxr-xr-x 3 root     root      4096 Feb 27  2023 logcheck
drwxr-xr-x 3 root     root      4096 Feb 27  2023 xml
drwxr-xr-x 3 root     root      4096 Feb 27  2023 java
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sudoers.d
drwxr-xr-x 3 root     root      4096 Feb 27  2023 pm
drwxr-xr-x 2 root     root      4096 Feb 27  2023 ldap
drwxr-xr-x 1 root     root      4096 Feb 27  2023 ssl
drwxr-xr-x 4 root     root      4096 Feb 27  2023 lighttpd
drwxr-xr-x 1 root     root      4096 Feb 27  2023 pam.d
drwxr-xr-x 2 root     root      4096 Feb 27  2023 cron.monthly
drwxr-xr-x 2 root     root      4096 Feb 27  2023 cron.hourly
-rw-r--r-- 1 root     root      5432 Feb 27  2023 ca-certificates.conf
drwxr-xr-x 3 root     root      4096 Feb 27  2023 xdg
drwxr-xr-x 4 root     root      4096 Feb 27  2023 fonts
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python
drwxr-xr-x 2 root     root      4096 Feb 27  2023 ssh
drwxr-xr-x 1 root     root      4096 Feb 27  2023 update-motd.d
drwxr-xr-x 5 root     root      4096 Feb 27  2023 java-11-openjdk
drwxr-xr-x 1 root     root      4096 Feb 27  2023 dpkg
drwxr-xr-x 2 root     root      4096 Feb 27  2023 bash_completion.d
drwxr-xr-x 2 root     root      4096 Feb 27  2023 groovy
-r--r----- 1 root     root       784 Feb 27  2023 sudoers
-rw-r--r-- 1 root     root        19 Feb 27  2023 subuid
-rw-r--r-- 1 root     root        19 Feb 27  2023 subgid
drwxr-xr-x 1 root     root      4096 Feb 27  2023 ld.so.conf.d
drwxr-xr-x 3 root     root      4096 Feb 27  2023 gdb
drwxr-xr-x 2 root     root      4096 Feb 27  2023 python3.8
drwxr-xr-x 3 root     root      4096 Feb 27  2023 ufw
drwxr-xr-x 1 root     root      4096 Feb 27  2023 php
-rw-r--r-- 1 root     root        17 Feb 27  2023 timezone
lrwxrwxrwx 1 root     root        36 Feb 27  2023 localtime -> /usr/share/zoneinfo/America/New_York
drwxr-xr-x 2 root     root      4096 Feb 27  2023 groff
drwxr-xr-x 2 root     root      4096 Feb 27  2023 calendar
-rw-r--r-- 1 root     root      9397 Feb 27  2023 locale.gen
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.weekly
-rw-r--r-- 1 root     root      2621 Feb 27  2023 mailcap
-rw-r--r-- 1 root     root       581 Feb 27  2023 profile
-rw-r--r-- 1 root     root      2319 Feb 27  2023 bash.bashrc
drwxr-xr-x 3 root     root      4096 Feb 27  2023 NetworkManager
drwxr-xr-x 3 root     root      4096 Feb 27  2023 dhcp
drwxr-xr-x 3 root     root      4096 Feb 27  2023 apparmor
drwxr-xr-x 1 root     root      4096 Feb 27  2023 X11
drwxr-xr-x 1 root     root      4096 Feb 27  2023 sysctl.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rcS.d
drwxr-xr-x 5 root     root      4096 Feb 27  2023 java-8-openjdk
drwxr-xr-x 3 root     root      4096 Feb 27  2023 cassandra
drwxr-xr-x 1 root     root      4096 Feb 27  2023 apparmor.d
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sysstat
drwxr-xr-x 2 root     root      4096 Feb 27  2023 sensors.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 profile.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 default
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.daily
drwxr-xr-x 1 root     root      4096 Feb 27  2023 cron.d
-rw-r----- 1 root     shadow     675 Feb 27  2023 shadow-
-rw-r----- 1 root     shadow     675 Feb 27  2023 shadow
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc6.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc5.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc4.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc3.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc2.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc1.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 rc0.d
drwxr-xr-x 3 root     root      4096 Feb 27  2023 postgresql-common
drwxr-xr-x 3 postgres postgres  4096 Feb 27  2023 postgresql
-rw-r--r-- 1 root     root      1252 Feb 27  2023 passwd-
-rw-r--r-- 1 root     root      1279 Feb 27  2023 passwd
drwxr-xr-x 1 root     root      4096 Feb 27  2023 logrotate.d
drwxr-xr-x 1 root     root      4096 Feb 27  2023 init.d
-rw-r----- 1 root     shadow     495 Feb 27  2023 gshadow-
-rw-r----- 1 root     shadow     503 Feb 27  2023 gshadow
-rw-r--r-- 1 root     root       598 Feb 27  2023 group-
-rw-r--r-- 1 root     root       606 Feb 27  2023 group
-rw-r--r-- 1 root     root     38873 Feb 27  2023 ld.so.cache
drwxr-xr-x 3 root     root      4096 Feb 27  2023 emacs
drwxr-xr-x 1 root     root      4096 Feb 27  2023 alternatives
drwxr-xr-x 1 root     root      4096 Feb 27  2023 apt
-rw-r--r-- 1 root     root       115 Sep 16 04:25 resolv.conf
-rw-r--r-- 1 root     root        16 Sep 16 04:25 hostname
-rw-r--r-- 1 root     root       263 Sep 16 04:25 hosts
theia@theia-u11203041:~/tmp$ cp /var/log/boostrap.log .
cp: cannot stat '/var/log/boostrap.log': No such file or directory
theia@theia-u11203041:~/tmp$ cp /var/log/bootstrap.log .
theia@theia-u11203041:~/tmp$ 
```
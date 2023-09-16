
Hands-on Lab: Getting Started with the Linux Terminal
```
theia@theia-u11203041:/home/project$ ls
theia@theia-u11203041:/home/project$ ls/
bash: ls/: No such file or directory
theia@theia-u11203041:/home/project$ ls /
bin   dev  home  lib32  libx32  mnt  proc  run   srv  tmp  var
boot  etc  lib   lib64  media   opt  root  sbin  sys  usr
theia@theia-u11203041:/home/project$ cd ~
theia@theia-u11203041:~$ cd .
theia@theia-u11203041:~$ pwd
/home/theia
theia@theia-u11203041:~$ /b
bin/  boot/ 
theia@theia-u11203041:~$ /b
bin/  boot/ 
theia@theia-u11203041:~$ cd ~
theia@theia-u11203041:~$ 

```

Second Try

```
theia@theia-u11203041:/home/project$ ls
theia@theia-u11203041:/home/project$ ls/
bash: ls/: No such file or directory
theia@theia-u11203041:/home/project$ ls /
bin   dev  home  lib32  libx32  mnt  proc  run   srv  tmp  var
boot  etc  lib   lib64  media   opt  root  sbin  sys  usr
theia@theia-u11203041:/home/project$ cd ~
theia@theia-u11203041:~$ cd .
theia@theia-u11203041:~$ pwd
/home/theia
theia@theia-u11203041:~$ /b
bin/  boot/ 
theia@theia-u11203041:~$ /b
bin/  boot/ 
theia@theia-u11203041:~$ cd ~
theia@theia-u11203041:~$ 

```
Hands-on Lab: Installing, Updating, and Working with Text Editors
```
theia@theia-u11203041:/home/project$ sudo apt update
Ign:1 https://storage.googleapis.com/download.dartlang.org/linux/debian stable InRelease
Ign:2 https://storage.googleapis.com/download.dartlang.org/linux/debian testing InRelease     
Ign:4 https://storage.googleapis.com/download.dartlang.org/linux/debian unstable InRelease    
Get:5 https://storage.googleapis.com/download.dartlang.org/linux/debian stable Release [944 B]
Get:6 http://ppa.launchpad.net/ondrej/php/ubuntu bionic InRelease [20.8 kB]                   
Get:7 https://packages.microsoft.com/ubuntu/18.04/prod bionic InRelease [3,617 B]             
Get:8 https://storage.googleapis.com/download.dartlang.org/linux/debian testing Release [940 B]
Get:9 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]                   
Get:10 https://storage.googleapis.com/download.dartlang.org/linux/debian unstable Release [945 B]
Get:11 https://storage.googleapis.com/download.dartlang.org/linux/debian stable Release.gpg [833 B]
Get:12 http://ppa.launchpad.net/ubuntu-toolchain-r/test/ubuntu bionic InRelease [20.8 kB]     
Get:13 https://storage.googleapis.com/download.dartlang.org/linux/debian testing Release.gpg [833 B]
Get:14 https://packages.microsoft.com/ubuntu/18.04/prod bionic/main amd64 Packages [259 kB]   
Get:15 https://storage.googleapis.com/download.dartlang.org/linux/debian unstable Release.gpg [833 B]
Get:17 https://packages.microsoft.com/ubuntu/18.04/prod bionic/main all Packages [2,182 B]    
Ign:3 https://downloads.apache.org/cassandra/debian 311x InRelease                            
Get:19 https://storage.googleapis.com/download.dartlang.org/linux/debian stable/main amd64 Packages [9,041 B]
Err:18 https://downloads.apache.org/cassandra/debian 311x Release                             
  404  Not Found [IP: 135.181.214.104 443]
Get:20 http://apt.postgresql.org/pub/repos/apt bionic-pgdg InRelease [122 kB]                 
Get:21 https://storage.googleapis.com/download.dartlang.org/linux/debian testing/main amd64 Packages [575 B]
Get:22 http://security.ubuntu.com/ubuntu bionic-security/multiverse amd64 Packages [23.8 kB]  
Get:23 http://security.ubuntu.com/ubuntu bionic-security/restricted amd64 Packages [1,688 kB] 
Get:16 https://apt.llvm.org/bionic llvm-toolchain-bionic InRelease [6,834 B]                  
Get:24 http://ppa.launchpad.net/ubuntu-toolchain-r/test/ubuntu bionic/main amd64 Packages [62.3 kB]
Get:25 https://storage.googleapis.com/download.dartlang.org/linux/debian unstable/main amd64 Packages [1,211 B]
Get:26 http://security.ubuntu.com/ubuntu bionic-security/main amd64 Packages [3,373 kB]       
Get:27 http://apt.postgresql.org/pub/repos/apt bionic-pgdg/main amd64 Packages [477 kB]       
Get:28 http://security.ubuntu.com/ubuntu bionic-security/universe amd64 Packages [1,636 kB]   
Get:29 https://apt.llvm.org/bionic llvm-toolchain-bionic/main amd64 Packages [14.3 kB]        
Get:30 http://archive.ubuntu.com/ubuntu bionic InRelease [242 kB]                             
Get:31 http://archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]
Get:32 http://archive.ubuntu.com/ubuntu bionic-backports InRelease [83.3 kB]
Get:33 http://archive.ubuntu.com/ubuntu bionic/universe amd64 Packages [11.3 MB]
Get:34 http://archive.ubuntu.com/ubuntu bionic/main amd64 Packages [1,344 kB]
Get:35 http://archive.ubuntu.com/ubuntu bionic/restricted amd64 Packages [13.5 kB]      
Get:36 http://archive.ubuntu.com/ubuntu bionic/multiverse amd64 Packages [186 kB]        
Get:37 http://archive.ubuntu.com/ubuntu bionic-updates/universe amd64 Packages [2,410 kB]
Get:38 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 Packages [3,785 kB]
Get:39 http://archive.ubuntu.com/ubuntu bionic-updates/multiverse amd64 Packages [30.8 kB]
Get:40 http://archive.ubuntu.com/ubuntu bionic-updates/restricted amd64 Packages [1,728 kB]
Get:41 http://archive.ubuntu.com/ubuntu bionic-backports/main amd64 Packages [64.0 kB]   
Get:42 http://archive.ubuntu.com/ubuntu bionic-backports/universe amd64 Packages [20.6 kB]
Reading package lists... Done                                 
E: The repository 'http://www.apache.org/dist/cassandra/debian 311x Release' does not have a Release file.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.
theia@theia-u11203041:/home/project$ sudo aptupgrade nano
sudo: aptupgrade: command not found
theia@theia-u11203041:/home/project$ sudo apt upgrade nano
Reading package lists... Done
Building dependency tree       
Reading state information... Done
nano is already the newest version (2.9.3-2).
Calculating upgrade... Done
The following NEW packages will be installed:
  gcc-13-base
The following packages will be upgraded:
  apache2 apache2-bin apache2-data apache2-utils apt apt-transport-https binutils
  binutils-common binutils-x86-64-linux-gnu ca-certificates ca-certificates-java containerd
  curl dart distro-info-data docker.io dotnet-host gcc-11-base git git-man iptables
  krb5-locales lib32atomic1 lib32gcc-s1 lib32gcc1 lib32gomp1 lib32itm1 lib32quadmath0
  lib32stdc++6 libapparmor1 libapt-inst2.0 libapt-pkg5.0 libatomic1 libbinutils libcc1-0
  libcups2 libcurl3-gnutls libcurl4 libgcc-s1 libgcc1 libgomp1 libgssapi-krb5-2 libip4tc0
  libip6tc0 libiptc0 libitm1 libk5crypto3 libkrb5-3 libkrb5support0 liblsan0 libncurses5
  libncurses5-dev libncursesw5 libobjc4 libperl5.26 libpq-dev libpq5 libpython2.7
  libpython2.7-dev libpython2.7-minimal libpython2.7-stdlib libpython3.6 libpython3.6-dev
  libpython3.6-minimal libpython3.6-stdlib libquadmath0 libruby2.5 libssl-dev libssl1.0.0
  libssl1.1 libstdc++6 libsystemd0 libtinfo-dev libtinfo5 libtsan0 libudev1 libunwind8
  libx32atomic1 libx32gcc-s1 libx32gcc1 libx32gomp1 libx32itm1 libx32quadmath0 libx32stdc++6
  libxstream-java libxtables12 libyaml-snake-java linux-libc-dev mysql-client
  mysql-client-5.7 mysql-client-core-5.7 ncurses-base ncurses-bin openjdk-11-jre-headless
  openjdk-8-jre-headless openssl perl perl-base perl-modules-5.26 postgresql-15
  postgresql-client-15 postgresql-client-common postgresql-common python-pip python-pip-whl
  python2.7 python2.7-dev python2.7-minimal python3-pip python3-software-properties python3.6
  python3.6-dev python3.6-minimal ruby2.5 ruby2.5-dev ruby2.5-doc runc
  software-properties-common sudo tar tzdata
121 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 438 MB of archives.
After this operation, 386 kB of additional disk space will be used.
Do you want to continue? [Y/n]  Y
Abort.
theia@theia-u11203041:/home/project$ sudo apt install vim
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  libgpm2 vim-common vim-runtime xxd
Suggested packages:
  gpm ctags vim-doc vim-scripts
The following NEW packages will be installed:
  libgpm2 vim vim-common vim-runtime xxd
0 upgraded, 5 newly installed, 0 to remove and 121 not upgraded.
Need to get 6,735 kB of archives.
After this operation, 32.6 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 xxd amd64 2:8.0.1453-1ubuntu1.13 [51.9 kB]
Get:2 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 vim-common all 2:8.0.1453-1ubuntu1.13 [73.1 kB]
Get:3 http://archive.ubuntu.com/ubuntu bionic/main amd64 libgpm2 amd64 1.20.7-5 [15.1 kB]
Get:4 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 vim-runtime all 2:8.0.1453-1ubuntu1.13 [5,439 kB]
Get:5 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 vim amd64 2:8.0.1453-1ubuntu1.13 [1,156 kB]
Fetched 6,735 kB in 0s (32.7 MB/s)     
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package xxd.
(Reading database ... 60840 files and directories currently installed.)
Preparing to unpack .../xxd_2%3a8.0.1453-1ubuntu1.13_amd64.deb ...
Unpacking xxd (2:8.0.1453-1ubuntu1.13) ...
Selecting previously unselected package vim-common.
Preparing to unpack .../vim-common_2%3a8.0.1453-1ubuntu1.13_all.deb ...
Unpacking vim-common (2:8.0.1453-1ubuntu1.13) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-5_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-5) ...
Selecting previously unselected package vim-runtime.
Preparing to unpack .../vim-runtime_2%3a8.0.1453-1ubuntu1.13_all.deb ...
Adding 'diversion of /usr/share/vim/vim80/doc/help.txt to /usr/share/vim/vim80/doc/help.txt.vim-tiny by vim-runtime'
Adding 'diversion of /usr/share/vim/vim80/doc/tags to /usr/share/vim/vim80/doc/tags.vim-tiny by vim-runtime'
Unpacking vim-runtime (2:8.0.1453-1ubuntu1.13) ...
Selecting previously unselected package vim.
Preparing to unpack .../vim_2%3a8.0.1453-1ubuntu1.13_amd64.deb ...
Unpacking vim (2:8.0.1453-1ubuntu1.13) ...
Setting up xxd (2:8.0.1453-1ubuntu1.13) ...
Setting up libgpm2:amd64 (1.20.7-5) ...
Setting up vim-common (2:8.0.1453-1ubuntu1.13) ...
Setting up vim-runtime (2:8.0.1453-1ubuntu1.13) ...
Setting up vim (2:8.0.1453-1ubuntu1.13) ...
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/vim (vim) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/vimdiff (vimdiff) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/rvim (rvim) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/rview (rview) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/vi (vi) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/view (view) in auto mode
update-alternatives: using /usr/bin/vim.basic to provide /usr/bin/ex (ex) in auto mode
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Processing triggers for mime-support (3.60ubuntu1) ...
Processing triggers for libc-bin (2.27-3ubuntu1.6) ...
theia@theia-u11203041:/home/project$ cd /home/project
theia@theia-u11203041:/home/project$ ls
theia@theia-u11203041:/home/project$ nano hello_world.txt
theia@theia-u11203041:/home/project$ cat hello_world.txt
Hello world!
This is the second line of my first-ever text file created with nano.
theia@theia-u11203041:/home/project$ vim
theia@theia-u11203041:/home/project$ vim hello_worl_2.txt
theia@theia-u11203041:/home/project$ nano hello_world.txt
theia@theia-u11203041:/home/project$ vim done.txt
theia@theia-u11203041:/home/project$ bash done.txt
I am done with the lab!
theia@theia-u11203041:/home/project$ 
```




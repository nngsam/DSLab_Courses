Hands-on Lab: Access Control Commands

```
theia@theia-u11203041:/home/project$ cd /home/project
theia@theia-u11203041:/home/project$ wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-LX0117EN-SkillsNetwork/labs/module%201/usdoi.txt
--2023-09-16 05:09:59--  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-LX0117EN-SkillsNetwork/labs/module%201/usdoi.txt
Resolving cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)... 169.63.118.104
Connecting to cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)|169.63.118.104|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 8121 (7.9K) [text/plain]
Saving to: ‘usdoi.txt’

usdoi.txt               100%[==============================>]   7.93K  --.-KB/s    in 0s      

2023-09-16 05:09:59 (908 MB/s) - ‘usdoi.txt’ saved [8121/8121]

theia@theia-u11203041:/home/project$ ls -l usdoi.txt
-rw-r--r-- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ chmod -r usdoi.txt
theia@theia-u11203041:/home/project$ ls -l usdoi.txt
--w------- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ chmod +r usdoi.txt
theia@theia-u11203041:/home/project$ ls -l usdoi.txt
-rw-r--r-- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ chmod o-r usdoi.txt
theia@theia-u11203041:/home/project$ ls -l usdoi.txt
-rw-r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ cd /home/project
theia@theia-u11203041:/home/project$ mkdir test
theia@theia-u11203041:/home/project$ ls -l
total 16
drwxr-sr-x 2 theia users 4096 Sep 16 04:37 scripts
drwxr-sr-x 2 theia users 4096 Sep 16 05:15 test
-rw-r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ cd test
theia@theia-u11203041:/home/project/test$ mkdir test2
theia@theia-u11203041:/home/project/test$ cd ../
theia@theia-u11203041:/home/project$ chmod u-x test
theia@theia-u11203041:/home/project$ cd test
bash: cd: test: Permission denied
theia@theia-u11203041:/home/project$ ls -l
total 16
drwxr-sr-x 2 theia users 4096 Sep 16 04:37 scripts
drw-r-sr-x 3 theia users 4096 Sep 16 05:16 test
-rw-r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ mkdir test/test3
mkdir: cannot create directory ‘test/test3’: Permission denied
theia@theia-u11203041:/home/project$ chmod u+x test
theia@theia-u11203041:/home/project$ chmod u-w test
theia@theia-u11203041:/home/project$ ls -l
total 16
drwxr-sr-x 2 theia users 4096 Sep 16 04:37 scripts
dr-xr-sr-x 3 theia users 4096 Sep 16 05:16 test
-rw-r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ cd test
theia@theia-u11203041:/home/project/test$ mkdir test_again
mkdir: cannot create directory ‘test_again’: Permission denied
theia@theia-u11203041:/home/project/test$ 

```
PRACTICE EXERCISE

```
theia@theia-u11203041:/home/project/test$ cd /home/project
theia@theia-u11203041:/home/project$ ls -l usdoi.txt
-rw-r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ chmod u-w usdoi.txt
theia@theia-u11203041:/home/project$ ls -l usdoi.txt
-r--r----- 1 theia users 8121 Sep 28  2022 usdoi.txt
theia@theia-u11203041:/home/project$ rv usdoi.txt
bash: rv: command not found
theia@theia-u11203041:/home/project$ rm usdoi.txt
rm: remove write-protected regular file 'usdoi.txt'? y
theia@theia-u11203041:/home/project$ ls usdoi.txt
ls: cannot access 'usdoi.txt': No such file or directory
theia@theia-u11203041:/home/project$ mkdir tmp_dir
theia@theia-u11203041:/home/project$ ls -ld tmp_dir
drwxr-sr-x 2 theia users 4096 Sep 16 05:22 tmp_dir
theia@theia-u11203041:/home/project$ chmod u-w tmp_dir
theia@theia-u11203041:/home/project$ cd tmp_dir
theia@theia-u11203041:/home/project/tmp_dir$ mkdir sub_dir
mkdir: cannot create directory ‘sub_dir’: Permission denied
theia@theia-u11203041:/home/project/tmp_dir$ mkdir tmp_dir/sub_dir
mkdir: cannot create directory ‘tmp_dir/sub_dir’: No such file or directory
theia@theia-u11203041:/home/project/tmp_dir$ 
```
Hands-on Lab: Getting Started with Shell Scripting

- Exercise 1 - Create and execute a basic shell script
```
theia@theia-u11203041:/home/project$ ls -l greet.sh
-rw-r--r-- 1 theia users 522 Sep 16 19:38 greet.sh
theia@theia-u11203041:/home/project$ bash greet.sh
Enter your name :nhungsam
Welcome nhungsam
Congratulations! You just created and ran your first shell script using Bash on IBM Skills Network
theia@theia-u11203041:/home/project$ 
```
- Exercise 2 - Using a shebang line
```
theia@theia-u11203041:/home/project$ which bash
/bin/bash
theia@theia-u11203041:/home/project$ chmod +x greet.sh
theia@theia-u11203041:/home/project$ chmod u+x greet.sh
theia@theia-u11203041:/home/project$ ls -l greet.sh
-rwxr-xr-x 1 theia users 535 Sep 16 19:40 greet.sh
theia@theia-u11203041:/home/project$ ./greet.sh
Enter your name :nhungsma
Welcome nhungsma
Congratulations! You just created and ran your first shell script using Bash on IBM Skills Network
theia@theia-u11203041:/home/project$ 
```

Practice Exercise
```
(base) samng@Sam-MacBook Week 3 % chmod u+x greetnew.sh
(base) samng@Sam-MacBook Week 3 % ./greetnew.sh
Enter your firstname :nhung
Enter your lastname :sam
Hello nhung sam.
```

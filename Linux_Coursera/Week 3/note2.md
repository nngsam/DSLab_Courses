Hands-on Lab: Advanced Bash Scripting

- ex1: conditional_script.sh
```
(base) samng@Sam-MacBook Week 3 % chmod u+x conditional_script.sh
(base) samng@Sam-MacBook Week 3 % ./conditional_script.sh
Are you enjoying this course so far?
Enter "y" for yes, "n" for no.y
I'm pleased to hear you are enjoying the course!
Your feedback regarding what you have been enjoying would be most welcome!
```
-ex2: two_numbers.sh
```
(base) samng@Sam-MacBook Week 3 % chmod u+x two_numbers.sh
(base) samng@Sam-MacBook Week 3 % ./two_numbers.sh
Enter an integer: 1
Enter another integer: 2
The sum of 1 and 2 is 3
The product of 1 and 2 is 2.
The sum is greater than the product.

```
- ex3: Using arrays for storing and accessing data within for loops
```
(base) samng@Sam-MacBook Week 3 % chmod u+x two_numbers.sh
(base) samng@Sam-MacBook Week 3 % ./two_numbers.sh
Enter an integer: 1
Enter another integer: 2
The sum of 1 and 2 is 3
The product of 1 and 2 is 2.
The sum is greater than the product.
(base) samng@Sam-MacBook Week 3 % csv_file="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-LX0117EN-SkillsNetwork/labs/M3/L2/arrays_table.csv"
wget $csv_file
zsh: command not found: wget
(base) samng@Sam-MacBook Week 3 % chmod u_x table_columns.sh
chmod: Invalid file mode: u_x
(base) samng@Sam-MacBook Week 3 % chmod u+x table_columns.sh
(base) samng@Sam-MacBook Week 3 % ./table_columns.sh
Displaying the first column:
column_0 1 4 7 10
There are        5 lines in the file
column_3 1 1 1 1
(base) samng@Sam-MacBook Week 3 % 

```
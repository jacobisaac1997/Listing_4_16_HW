# Listing_4_16_HW: How to generate a random uppercase letter

##Introduction

This document details the generation of a Java program that writes an uppercase letter to the console. This code is managed insides Github.com and uses the Math.random() method as well as a custom method call.

##Outline
```java
//Generate a random uppercase letter (using a custom method call)
//Print a random letter to the console.
```

## References and Literature
//Liang Java 10th edition. Pg 87, Listing 3.3
//This is an example of how to make a random number.
//int number1 = (int)(Math.random()*10);

//Liang Java 10th edition. Pg 125, Table 4.4
//We can map from integers to capital letters
//Characters ‘A’ to ‘Z’
//Code Value in decimal 65 to 90.

//Liang Java 10th edition. Pg 122, 4.2.5 the random method.
// a + Math.random() * b
//returns a random number between a and a+b, excluding a+b.

//Liang Java 10th edition. Pg 209, void Method Example
//This shows up how we can set up a method call.

##Code

##Console

##Command Prompt



1. Open Eclipse and start a new project
	a. may need to change your workspace
2. Go to Github and start a new repository.
3. Use the command prompt to navigate to the correct drive using dir when necessary.

Moves to the E: drive:
```
C:\Users\LAB>E:
```
*cd Eclipse G changes to the correct workspace
```
E:\>cd "Eclipse G"

E:\Eclipse G>cd Listing_4_16_HW
```

*Using dir to see what is in the folder
```
E:\Eclipse G\Listing_4_16_HW>dir
 Volume in drive E has no label.
 Volume Serial Number is 3892-20E5

 Directory of E:\Eclipse G\Listing_4_16_HW

11/02/2015  09:14 AM    <DIR>          .
11/02/2015  09:14 AM    <DIR>          ..
11/02/2015  09:14 AM               391 .project
11/02/2015  09:14 AM    <DIR>          src
11/02/2015  09:14 AM    <DIR>          bin
11/02/2015  09:14 AM               232 .classpath
11/02/2015  09:21 AM                20 README.md
               3 File(s)            643 bytes
               4 Dir(s)  15,823,241,216 bytes free
```

Continue to work through the instructions.

*initialize the repository.
E:\Eclipse G\Listing_4_16_HW>git init

Initialized empty Git repository in E:/Eclipse G/Listing_4_16_HW/.git/

*added files to the staging area
E:\Eclipse G\Listing_4_16_HW>git add .

*commited those files
E:\Eclipse G\Listing_4_16_HW>git commit -m "first commit"
[master (root-commit) 5f0e955] first commit
 6 files changed, 29 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 README.md
 create mode 100644 bin/Listing_4_16_HW.class
 create mode 100644 src/Listing_4_16_HW.java
 create mode 100644 ~$README.md

*pushed the master branch to the remote repository
E:\Eclipse G\Listing_4_16_HW>git remote add origin https://github.com/jacobisaac
1997/Listing_4_16_HW.git
E:\Eclipse G\Listing_4_16_HW>git push -u origin master
Username for 'https://github.com': jacobisaac1997
Password for 'https://jacobisaac1997@github.com':
Counting objects: 10, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (7/7), done.
Writing objects: 100% (10/10), 1.35 KiB | 0 bytes/s, done.
Total 10 (delta 0), reused 0 (delta 0)
To https://github.com/jacobisaac1997/Listing_4_16_HW.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

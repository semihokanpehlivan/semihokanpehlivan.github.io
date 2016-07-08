---
layout: post
title:  "Amazing Git tips -Bare Repos, Clone, Config and Pull- "
categories: jekyll update
---

#### Bare Repositories

-	Before explaining the bare repositories, you have seen some question like what is the different
between ```git init``` and ```git init --bare```? 
-	They are similar concept but they have just a little bit distinctness. Okay! the most explicit attribure of bare repositories is to not have working copy file. The repositories controll all working copy files and we can say basicly. The working copy files are files which developers work on. Working copy files may be named as working tree files. We cannot create new file(s) on bare reporsitories directly. You can clone the bare repositories and add new file(s) narrowly.
-	And also we can use bare repositories to work with our servers.

-	How to create bare repository

-	in the directory which you want to create bare repositories type the following command as follows:

![image](/images/img.png)

-	after creating the bare repository, you can controll the subfolder of it. It must be like that:

![image](/images/bare2.png)

***Note:*** When you create a new bare repository, don't forget to suffix the ~~~.git~~~ to repository name.

---
layout: post
title:  "Alias in Command-lines"
categories: Operating Systems
---
Essentially, we use the command-line to solve some spesific problem or obtain information of any application. we got used to execute program which have cute and user-friendly interfaces(even use the mouse). If we say that, in the world, there are some program but it has no interface which is created for 21th century users :). It has no mouse action, a tool bar or navigator e.g. 

For example: I am using the text editor to write this article, the excellent program has a perfect navigator, multi-tabs, info about line and column number update so on.

well, we learned that there could be programs without interface.

![OMG](https://media.giphy.com/media/jrV1bRhWXr9Di/giphy.gif)

we use the terminal to run that devilish programs by using some command like as follows:

~~~~~
# ==> this command say that sir, please create new directory in current directory
~username $ mkdir <new-directory-name>
# ==> have you ever seen the rigth-click and create new folder or directory
# ==> it was so easy to write and run.
~~~~~

we can run some set of commands in order. for example:
~~~~~
~username $ git status
~username $ git add .
~username $ git commit -am "Initial commit"
~username $ git push -u origin master
~~~~~

Alright, how can we curtail these commands, we must create `.bash_profile`(hidden file) in `User` directory. We can see the all file in current directory using other command below:

~~~~
~username $ ls -a
~~~~

In `.bash_profile`, add the new alias' like:

~~~~~BASH
alias gs="git status"
alias ga="git add ."
alias gc="git commit -am"
alias gp="git push"
alias gpl="git pull"
.....
alias jv="java --version"
~~~~~

Make sure that you save the `.bash_profile` and restart the terminal have fun when using you new commands :).

*Spare enough time to your computer*


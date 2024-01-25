---
layout: essay
type: essay
title: "tech essay"
date: 2024-01-1
published: false
labels:
  - smart question
  - stackoverflow
  - essay
---

Smart Question:
Failed Attempts to Delete a Remote Branch:

$ git branch -d remotes/origin/bugfix
error: branch 'remotes/origin/bugfix' not found.

$ git branch -d origin/bugfix
error: branch 'origin/bugfix' not found.

$ git branch -rd origin/bugfix
Deleted remote branch origin/bugfix (was 2a14ef7).

$ git push
Everything up-to-date

$ git pull
From github.com:gituser/gitproject

* [new branch] bugfix -> origin/bugfix
Already up-to-date.
How do I properly delete the remotes/origin/bugfix branch both locally and remotely?

Not Smart Question:
File "C:\Users\Administrator\Documents\Mibot\oops\blinkserv.py", line 82, in __init__
    self.serv = socket(AF_INET,SOCK_STREAM)
TypeError: 'module' object is not callable

Why am I getting this error? I'm confused.
How can I solve this error?


References(URL):
Smart Question: https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely
Not Smart Question: https://stackoverflow.com/questions/4534438/typeerror-module-object-is-not-callable

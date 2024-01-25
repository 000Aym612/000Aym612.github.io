---
layout: essay
type: essay
title: "Is your question smart enough?"
date: 2024-01-24
published: true
labels:
  - smart question
  - stackoverflow
  - essay
---
## What defines your question as a smart question or not?


### Smart Question:
##### Q: Failed Attempts to Delete a Remote Branch:
##### How do I properly delete the remotes/origin/bugfix branch both locally and remotely?
  
```
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
```

### Smart questions ususally have to provide:
 (Information): Needs to provide information as much as possible to make your problem clear enough for reviewrs.
 
 (Efficiency): Needs to explain what you have tried already for an efficiency of reviewrs.
 
 (Expectation): Needs to refer to what you expected the code do or look like.
 
 (Comparison) :Needs to refer to how its result different from what you expected.




### Not Smart Question:

```
File "C:\Users\Administrator\Documents\Mibot\oops\blinkserv.py", line 82, in __init__
    self.serv = socket(AF_INET,SOCK_STREAM)
TypeError: 'module' object is not callable
```

##### Q: Why am I getting this error? I'm confused.
##### How can I solve this error?

### Not smart questions do not satisfy enough elements stated above:
##### In this case:
 Lack of expectation -> How do you want to change the result?
 
 Lack of efficiency -> Did you look up it by yourself?
 
 Lack of comparison -> How the result differed from what you expected?


### References(URL):
###### Smart Question: https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely
###### Not Smart Question: https://stackoverflow.com/questions/4534438/typeerror-module-object-is-not-callable

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

<img class="img-fluid" src="../img/smart2.png" auto>


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

#### What is expected in a smart question?
When posing smart questions, especially in the context of seeking help or clarification, it is critically important to include as much information as possible. This detail ensures that your problem is sufficiently clear for reviewers to understand, which also contributes to what you would get an answer on. By providing background information, specific details about the issue, and any relevant context, you allow those who are assisting you to be able to see the full scope of your question. In other words, when you provide information to others, the information has to be clear and helpful to make it clear what makes you get in trouble. This comprehensive approach aids in minimizing assumptions and guesswork, leading to more accurate and helpful responses.


Additionally, it is crucial to mention what you have already tried to resolve your issue. This shows the reviewers that you have put in effort to solve the problem and helps them understand the steps you have taken. Consequently, that ensures efficiency in their review process and saves their wast effort on your work! you should consider that they spend their time for helping you! You should also clearly state your expectations - what you hoped your code or solution would achieve or look like. Furthermore, if your results differ from your expectations, make sure to describe how it is different or how you want to change it. A comparison between the expected outcome and the actual result provides valuable insight into the nature of the problem, making it easier for others to offer targeted and effective assistance.




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

<img class="img-fluid" src="../img/smart1.jpg" auto>

#### How can you improve the not smart question?
 The example provided what we called a not smart question that fails to meet the criteria of a smart question I mentioned above. It lacks a clear expectation: the person who asked a question has not specified what they intended to achieve with their code. They only presented an error message and asked for a solution without describing the expected output or what they were hoping for as a result of the function. This lack of expectation makes it challenging for others to offer precise advice or solutions, as they have no context about what the code is supposed to do. Smart questions need to convey a clear goal or expected behavior, so responders can tailor their advice accordingly. Without that, answers may only address the superficial aspects of the problem(like only explaining syntax errors) or the reviewer may answer with his misunderstanding without tackling the underlying functional issues.

 
Besides that, the question demonstrates a lack of efficiency. The person who asked a question does not mention details on the attempts he have made to solve the issue, such as researching the error message or trying different coding approaches. This absence suggests that they might be relying solely on others for a solution, without putting in adequate effort to address the problem themselves. Demonstrating self-reliance and initiative, like looking up the error or experimenting with alternative solutions, is crucial in smart questions. It not only shows a willingness to learn but also provides others with a baseline of what has been tried, enabling more focused and advanced assistance. The question fails to provide a comparison between the expected and actual outcomes. There is no mention of how the results deviated from what was anticipated, leaving potential helpers in the dark about the specific nature of the problem. A smart question would clearly articulate these discrepancies, making it easier for others to pinpoint the issue and offer relevant, effective solutions.


## References(URL):
### Images:
https://www.irasutoya.com/2014/01/q.html
https://www.smartsheet.com/blog/essential-guide-writing-smart-goals

###### Smart Question: https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely
###### Not Smart Question: https://stackoverflow.com/questions/4534438/typeerror-module-object-is-not-callable

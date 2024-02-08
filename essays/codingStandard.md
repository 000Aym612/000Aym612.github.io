---
layout: essay
type: essay
title: "Collaborative programming"
date: 2024-02-08
published: true
labels:
  - coding standard
  - group(team) projects
---

## What is the advantages of coding standard?
One of the definitions of the coding standard says that it is a guideline to allow you and your colleagues to work effectively by defining some rules corresponding to a project.
Since I entered university, I have been taking a bunch of coding classes. Some classes required me to use Java as a programming language, another class required me to use Python, C/C++ or R as a programming language. They all asked me to use different languages or different ways. However, most classes also gave me guidelines for writing a code. Now, I have realized they were a part of the coding standard. The first time I saw it and I had to follow the rules, I really felt uncomfortable because of unfamiliarity with it. The way to write a code is much different from what I usually do, each difference is such a small thing. 


### Example: Use ' \\\\ ' when you comment multiple lines.
#### When I wanted to comment two or more sentences like:

```
/* 
 * The function return sum of numbers
 * The function takes 2 numbers as parameters
 * function summation(num1, num2){...}
 */

/* I usually use '/*' symbol to put multiple comments!
```

#### However, I have to type them in this way:

```
//The function return sum of numbers
//The function takes 2 numbers as parameters
function summation(num1, num2){...}

// I have to use '//' symbol twice to put multiple comments!
```

Now, let’s take a look at the features of the coding standard and a few advantages.

## Some examples of the guidelines I found them helpful:

**Naming conventions for variables:**
It prevents team members or readers from misunderstanding what a variable represents or highlights the readability of your code as well as clarifying what you intend a variable to hold.

**Let's say there is a variable to store the value of the number of heads in 100 times of coin flips.**

If you use a variable named **num**, the reader might get misunderstood that the variable represents the number of coins flipped!
```
function coinFlip() {
    times = 100;
    num = 0;
    for(let i = 0; i < 100; i++) {
        random( 1 or 0 )
        if (random === 1) {
            num++;
        }
    }
    return num;
}
```

In this case, using a variable name such as **numOfHeads** is preferable.

```
function coinFlip() {
    times = 100;
    numOfHeads = 0;
    for(let i = 0; i < 100; i++) {
        random( 1 or 0 )
        if (random === 1) {
            numOfHeads++;
        }
    }
    return numOfHeads;
}
```

**Code structure:** Well-structured code ensures that each small part of the program is clearly defined, significantly boosting both the modularity and reusability of the program. This clarity in structure makes the entire codebase much easier to understand. Moreover, it simplifies the process of sharing intentions among team members, such as understanding what the team is going to build or how they plan to make functions work.

#### Example of using class method

```
class Employee:
    num_employees = 0

    def __init__(self, name, position):
        self.name = name
        self.position = position
        Employee.increment_num_employees()

    def increment_num_employees(cls):
        cls.num_employees += 1

    def get_num_employees(cls):
        return cls.num_employees

emp1 = Employee("John Doe", "Software Engineer")
emp2 = Employee("Jane Doe", "Project Manager")

print(Employee.get_num_employees())
```
**Ex. Formatting style, Guidelines for writing comments, Naming conventions, Programming practices, etc.**

## A coding standard builder is a hard worker!!
From a different perspective, implementing coding standards can be seen as somewhat challenging. Suppose, you are about to collaborate with five team members to build a database that manages company employee data. This database is supposed to be used for the next ten years and is expected to be edited by individuals other than the original creators, therefore the CEO has asked you to create a coding standard for the future. With the project just starting and everything still in the planning phase, you need to consider what will be necessary and what rules could be helpful for those who will modify the program in the future. Since we cannot predict the future, this can be quite difficult. Of course, if the initial setup is challenging, you can change or add a rule once after the project starts, but such modifications could cause the violation of previously written programs against the new rules. Considering these aspects, while coding standards enhance efficiency and teamwork for users, they can be daunting for the creators to establish.

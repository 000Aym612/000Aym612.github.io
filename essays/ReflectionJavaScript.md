---
layout: essay
type: essay
title: "My first practice of JavaScript!"
date: 2024-01-1
published: true
labels:
  - Software Engineering
  - Comparison with other languages
  - JavaScript
---

## How do you feel on JavaScript in general? Should I use it?  


### How I am feeling on JavaScript as a programming language compared with Python, Java, C/C++.
  I feel JavaScript is between Python and Java in terms of its functionality and style of coding. For example, when I create a function with a few parameters, in Java, C or C++, I have to define what data type of parameter I would pass and I have to define what data type of the function is, which means what data type of output the function returns after calling. This feature sounds like more Python than Java or C languages. Besides that, I do not have to write code inside a main function unlike Java or C do. However, in terms of grammar, such as switch statements, increment/decrement operators, I feel it is more similar to Java or C.

In Java:
```
1: class sample {
2:   // Supposed we have a class Array
3:   public static void main(String args[]) {
4:     Array arr = new Array();
5:     arr = [num1, num2, num3, ..., numN];
6:     HeapSOrt(arr);
7:   }
8:
9:   public static void HeapSort(Arrray arr) {
10:     // do heap sort
11:  }
12: }
```

In JavaScript:
```
1: class sample {
2:   costructor(arr) {
3:      this.arr = arr;
4:    }
5:    HeapSort(this.arr);
6:  }
7:  // define an array as arr;
9:  mySample = new sample(arr);
10: mySample.HeapSort(arr);
```

  As it is written above, we need to declare which data type the array arr(Java: line3 & line8) is. On the other hands, in JavaScript, we do not ned to declare it(JavaScript: line2 & line9) which means we are not restricted to a data type, but a datatype is expected to be passed as a parameter of a class.


### Is JavaScript useful or useless?
  I am not sure if this language is useful for soft engineering yet since I did not have an experience of JavaScript before the class and I did not get used to it. Additionally, the WOD is useful for me to practice this language in a more practical way. One problem I face when I start programming is that I do not have an idea how to apply the elemental knowledge of the language to any application or what I want to do. Thanks to the WOD, I feel it is clearly testing your understanding of this language and leading us in the right direction.

### What is an expected concern to lean JavaScript?
  One concern for now is JavaScript requires me to do HTML/CSS at the same time to use it, but I am not familiar with them, even though I have experience with them. Even though those languages are quite different from other languages, especially what I usually use for data science or data analysis, I am kind of worried about it.

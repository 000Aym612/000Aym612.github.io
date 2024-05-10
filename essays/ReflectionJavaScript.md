---
layout: essay
type: essay
title: "My first practice of JavaScript!"
date: 2024-01-18
published: true
labels:
  - Software Engineering
  - Comparison with other languages
  - JavaScript
---

<img class="img-fluid" src="../img/javascriptCapture.jpg"
  width="400" 
  height="400">
  <img class="img-fluid" src="../img/javascriptcap2.jpg"
  width="500" 
  height="300">



## How do you feel on JavaScript in general? Should I use it?  


### How I am feeling on JavaScript as a programming language compared with Python, Java, C/C++.
  I feel JavaScript is between Python and Java in terms of its functionality and style of coding. For example, when I create a function with a few parameters, in Java, C or C++, I have to define what data type of parameter I would pass and I have to define what data type of the function is, which means what data type of output the function returns after calling. This feature sounds like more Python than Java or C languages. Besides that, I do not have to write code inside a main function unlike Java or C do. However, in terms of grammar, such as switch statements, increment/decrement operators, I feel it is more similar to Java or C.

### In Java:
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

### In JavaScript:
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

  As it is written above, we need to declare which data type the array arr(Java: line3 & line8) is. On the other hands, in JavaScript, we do not need to declare it(JavaScript: line2 & line9) which means we are not restricted to a data type, but a datatype is expected to be passed as a parameter of a class.


### Is JavaScript useful or useless?
  I am not sure if this language is useful for soft engineering yet since I did not have an experience of JavaScript before the class and I did not get used to it. Additionally, the WOD is useful for me to practice this language in a more practical way. One problem I face when I start programming is that I do not have an idea how to apply the elemental knowledge of the language to any application or what I want to do. Thanks to the WOD, I feel it is clearly testing your understanding of this language and leading us in the right direction.

Even though I have an experience of other languages, there are always concerns. One concern for now is JavaScript requires me to do HTML/CSS at the same time to use it, but I am not familiar with them. Python is widely used in backend development, such as the fields like AI development and data science. While HTML/CSS and JavaScript are focusing on different aspects of programming and web development. HTML (HyperText Markup Language) and CSS (Cascading Style Sheets) are languages used to define the structure and style of web pages. HTML makes the content and basic structure of web pages with CSS customization on the layout and design of this content. These are a markup language (HTML) and a style sheet language (CSS). Additionally, JavaScript is a programming language that adds dynamic elements and interactivity to web pages. For example, a famous framework React enables the pages to refresh fast. which prevents double booking from users to reserve airplane seats. It operates within web browsers and can dynamically change the content of a page in response to user inputs or perform asynchronous communications.


Python is a versatile, high-level programming language used for a wide range of applications and scripting. It's employed in various domains from web development to data analysis, scientific computing, and artificial intelligence.
While HTML/CSS and JavaScript are primarily specialized in web development, Python is not typically used in the same context, such as for data analysis or scientific computing. Thus, these languages serve different roles and are used in different environments. In the context of web development, they have a complementary relationship.


## Reference of Images:
<a href="https://radixweb.com/blog/javascript-practices-and-tools">https://radixweb.com/blog/javascript-practices-and-tools</a>

<a href="https://www.thoughtco.com/what-is-javascript-2037921">https://www.thoughtco.com/what-is-javascript-2037921</a>


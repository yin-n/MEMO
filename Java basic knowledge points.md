### Casual study notes

------

*date: 08/22/2021*

*name: yin*

*tag: Java basic knowledge points*

- #### Overriding vs Overloading

<p align="center">
  <img src="https://github.com/yin-n/memo/blob/main/image/overriding%26overloading.JPG" style="zoom:67%;" />
</p>

​		Reference:

​        [Click here](https://www.runoob.com/java/java-override-overload.html)

- #### Declaration vs Definition

  The conceptual difference is simple:

  - *Declaration*: You are *declaring* that something exists, such as a class, function or variable. You don't say anything about *what* that class or function looks like, you just say that it exists.
  - *Definition*: You *define* how something is implemented, such as a class, function or variable, i.e. you say *what* it actually is.

  **In Java**, there is little difference between the two, and formally speaking, a declaration includes not only the identifier, but also it's definition.

  memorizable via: de-finite, fin = end, "to finish it"; de-clare, clarus = clear, "to make it clear". Declaration makes clear of existence, type and name. Definition is the "real work" code after which you can "finish talking about it". They're used language-agnostic so your question means, what's Java's use of these general concepts. 

  Reference:

  [English-version](https://stackoverflow.com/questions/11715485/what-is-the-difference-between-declaration-and-definition-in-java)

  [Chinese-version](https://blog.csdn.net/jingzhesiye/article/details/40297085)

- #### Compiler vs Interpreter

<p align="center">
  <img src="https://github.com/yin-n/memo/blob/main/image/compiler%26interpreter.JPG" style="zoom:80%;" />
</p>
  

  A **compiler** is a computer program (or a set of programs) that transforms source code written in a programming language (the source language) into another computer language (the target language), with the latter often having a binary form known as object code. The most common reason for converting source code is to create an executable
  program.

<p align="center">
  <img src="https://github.com/yin-n/memo/blob/main/image/compile%20process.JPG" style="zoom:50%;" />
</p>

  In computer science, an **interpreter** is a computer program that directly executes, i.e. performs, instructions written in a programming or scripting language, without previously compiling them into a machine language program. An interpreter generally uses one of the following strategies for program execution: parse the source code and perform its behavior directly. translate source code into some efficient intermediate representation and immediately execute this. explicitly execute stored pre-compiled code made by a compiler which is part of the interpreter system.

  Reference:

  [English-version](https://stackoverflow.com/questions/2377273/how-does-an-interpreter-compiler-work)

  [Chinese-version](https://huang-jerryc.com/2016/11/20/do-you-konw-the-different-between-compiler-and-interpreter/)

------

*date: 08/22/2021*

*name: yin*

*tag: Android development*

- #### PlainText vs TextView

  **Plaintext** is nothing but the **Edittext**. It has changed the name in **Android studio** but if you check into Design view you will get to know that it still has name of **Edittext** only.

  **Usages**

  **Textview** : should be used for uneditable text which user wants to read but not to manipulate. e.g. News, Articles, Blogs.

  **Plain text/ Edittext** : should be used for taking user input in alphanumeric form. e.g. UserId, Comments.


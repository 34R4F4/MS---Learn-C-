# Learn C# | Microsoft Official Collection

## Unit 1 - Introduction

The C# programming language allows you to build many types of applications, like:

  - Business applications to capture, analyze, and process data
  - Dynamic web applications that can be accessed from a web browser
  - Games, both 2D and 3D
  - Financial and scientific applications
  - Cloud-based applications
  - Mobile applications

in this module, you'll:

  - Write your first lines of C# code.
  - Use two different techniques to print a message as output.
  - Diagnose errors when code is incorrect.
  - Identify different C# syntax elements like operators, classes, and methods.


---

## Unit 2 - Exercise - Write your first code

### Write your first line of code

```C#
Console.WriteLine("Hello World! i am Arafa");
```
~~~
Hello World! i am Arafa
~~~

### What to do if you get an error message

Writing C# code is an *`exercise in precision`*. If you type just one character incorrectly, you'll get an error message in the output area when you run the code.
For example, if you were to incorrectly enter a lower-case `c` in the word `console` like so:

```C#
console.WriteLine("Hello World!");
```
You'd get the following error message:
~~~
(1,1): error CS0103: The name 'console' does not exist in the current context
~~~
(1,1) (`line`, `column`)

*C# is a case-sensitive language*
C# compiler considers `console` != `Console`


Sometimes, the error message can be a bit misleading.
Similarly, if you used single-quotation marks (') to surround the literal string `Hello World!` like so:


```C#
Console.WriteLine('Hello World!');
```
You would get the following error message:
~~~
(1,19): error CS1012: Too many characters in character literal
~~~


Common mistakes new programmers make:

  - Entering lower-case letters instead of capitalizing `C` in `Console`, or the letters `W` or `L` in `WriteLine`.
  - Entering a comma`,` instead of a period`.` between `Console` and `WriteLine`.
  - Forgetting to use double-quotation marks, or using single-quotation marks to surround the phrase Hello World!.
  - Forgetting a semi-colon`;` at the end of the command.

Each of these mistakes prevents your code from compiling successfully.

### Display a new message

#### Comment

Comment with two forward slashes `//`

```C#
// this is comment 
```
~~~
No output
~~~


```C#
//Console.WriteLine("Hello World! i am Arafa");

Console.Write("Congratulations Arafa");
Console.Write(" ");
Console.Write("I wrote My first lines of C# code");
```
~~~
Congratulations Arafa I wrote My first lines of C# code
~~~

#### The difference between Console.Write and Console.WriteLine
`Console.WriteLine`  prints message and add new line.
`Console.Write`  prints message to the same line.  

---

```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~




```C#
```
~~~
~~~










```C#
```
~~~
~~~





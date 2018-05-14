---
layout: post
title: "Variables and Inputs"
quote: Hey come back!
image: /assets/posts/2018-05-15-variables-and-inputs/michael-mroczek-182813-unsplash.jpg
comments: true
video: false
dark: false
desc: "Learning Variables and Inputs"
tags: functions
---

Today we are going to start using Python as a programming language, starting with Inputs and Variables

## Inputs

### What is an input?

Inputs are the way you get `input` from the user, you can store their responeses in a variable.

### How do I ask for a number/text?

There are different types of Variables the main we will be using today will be `str` (text) and `int` (numbers)
 
For example:
```python
x = 4
```

Would make x equal 4 (an int)

On the other hand:
```python
x = "four"
```
Would make x equal four (a string)
<br>
<br>
Another way to illustrate this is if you typed

```python
x = 4
print(x+3)
```

It would output

```
7
```

On the other hand if you wrote
```python
x = "four"
print(x+3)
```

It would come out as a syntax error
<br>
<br>
### Taking inputs and making them variables

Let's say you wanted to ask somebodies name. One way you could do it is by writing this:

```python
name = input("What is your name?: ")
```

<br>

The code would be simply asking the user an input through the `input` function and would be setting that to a variable called <b>name</b>

We could call this function by simply printing it

For example:
```python
name = input("What is your name?: ")
print("Hello " + name)
```
<div class="message2">Notice that I used a space between "Hello " and + name, that is because if you just left it there it would mush the two together (e.g. HelloJeff)</div>

If I said my name was Jeff it would output
```
Hello Jeff
```

Now lets say we wanted to take down age as a variable as well (we will take it down as an `int`). The way you ask for an int in Python is like this:
```python
age = int(input("What is your age?: "))
```
This is because inputs are automatically taken down as a string and we want to ask for an `int`.

Now if we were to implement this into our code:
```python
age = int(input("What is your age?: "))
name = input("What is your name?: ")
print("Hello " + name + " you are " + age)
```
If we were to run this it would be a syntax error, this is because you are mixing int's and strings. A good way to think of this is you can't add `"red"` and `4`, you have to convert 4 in to a string first, the way we do this is by putting as `str` around it

```python
age = int(input("What is your age?: "))
name = input("What is your name?: ")
print("Hello " + name + " you are " + str(age))
```

### Addition Calculator

To test what we have learned we are going to be making a basic addition calculator try doing it yourself before you continue.

We need two variables, x and y, we will be adding these two variables.

When you finish it should like this
```python
x = int(input("Number 1: "))
y = int(input("Number 2: "))
print(str(x) + " + " + str(y) + " = " + str(x + y))
```

### Conclusion
Congratulations! You have taken the first big leap into becoming a programmer. Variables are bread and butter for programming and are essential in every program. Next week we will be going onto `if` statements
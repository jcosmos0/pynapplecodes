---
layout: post
title: "If, Else"
quote: If this then do that
image: /assets/posts/2018-05-22-starting-condition-statements/if-else.jpg
comments: true
video: false
dark: false
desc: "A start on If and Else statements"
tags: functions
---

So, imagine you have a number, and I want to guess your number. I can ask if your number is greater than 50, if it is then do this, otherwise do that. That is going to be the topic of todays blog post. We are going to be using the `if` and `else`.

### Syntax of an if statement
So when you want to ask Python to compare two things, how do you do it?

#### Comparing Numbers
When you want to compare numbers it is pretty simple we will be focusing on five different symbols, `>` (greater than), `<` (less than), `>=` (greater than or equal to), `<=` (less than or equal to) and `==` (equal to). Be careful that you do not just use one `=`, because one `=` is setting, while `==` is comparing.

Examples:
```python
if 3 > 4:

```

So when you see that you notice a few things, first the if, that is the function we are calling on, next is the > (greater than), literally just finds out if 3 is greater than 4. The next thing is the colon, anything under the colon which is indented is going to happen if 3 is greater then 4 (which is never).

You may notice I said we need an indent, this is essential if you don't use an indent it will return a syntax error.

Example:

This would be correct
```python
if 3 > 4:
    print("Hello")

```

While this would be incorrect:
```python
if 3 > 4:
print("Hello")

```

#### Password
For this next example we are going to be creating a password, which is going to be a `str`, we are going to be creating the user input, (a str) and we are going to be making a condition statement. If the password is correct it should output, `Password Correct!`. See if you can do it yourself!

When you have finished your code should look something like this:
```python
userInput = input("Password: ")
password = "qwertyuiop"
if userInput == password:
    print("Password Correct!")
```


### Syntax of an else statement
Else statements don't need any conditions, they simple are what the `if` statement is not.

For example in the password example we could add an else statement that simply replied `Password Incorrect` to any passwords that aren't the password.
```python
userInput = input("Password: ")
password = "qwertyuiop"
if userInput == password:
    print("Password Correct!")
    
else:
    print("Password Incorrect!")
```


### Elif
Elif statements are extremely simple, they are an if statement inside an else statemnt in one. Another way to think of it is they are second in the priority list, first comes `if`, then `elif`, then `else`.

Unlike else statements they need conditions (like an if statement).

Back to our password example, lets create another password called, "password overide". We'll use an elif statement for password overide.
```python
userInput = input("Password: ")
password = "qwertyuiop"
overide = "overide1234"
if userInput == password:
    print("Password Correct!")
elif userInput == overide:
    print("Password Overided!")
else:
    print("Password Incorrect!")
```



### Conclusion
Well done! You can now ask Python basic things. This is your next big step in learning to code. The next few weeks will build a foundation which we will then build on! Next week we will be bringing what we have done so far into a basic calculator.


---
layout: post
title: "Python, a Calculator"
quote: Hey come back!
image: /assets/posts/2018-04-31-python-the-worlds-most-powerful-calculator/charles-deluvio-456506-unsplash.jpg
comments: true
video: false
dark: false
desc: "Exploring maths in Python"
tags: functions
---

Today we are going to be focusing on Python's calculation ability.
We are going to be exploring the alternatives for Math's symbols in python and different data sets in python (ones specifically for maths).

### Different data types
There are 4 main datatypes for maths in Python, though we are going to be focusing on `int` and `floats`
| Data Type     | Definition                                    | Example                                   |
| ------------- |:---------------------------------------------:|:-----------------------------------------:|
| `long`        | Long numbers (can also be reperesented in hex)| `3212421124241dsasdasadsadsad321221424234`|
| `int`         | Whole Numbers                                 | `10`                                      |
| `float`       | Numbers with a floating point (Decimals)      | `4.2`                                     |
| `complex`     | Complex numbers                               | `2.71j`                                   |

### Which should I use
Generally you wouldn't use `complex` and `long`, but there are some places where you would use it.

If you are deciding between `float` and `int`, it just depends, if you want to use just whole numbers then use `int`, but if you want to use a number with a decimal place, then use `float`

### How do I tell which is which.
You can use the table above, but if you want to be sure you can always type in
```python
type(3)
```
It would output:

```
<class 'int'>
```

### Mathematical operators
Some of the symbols are pretty self explanitory, but others are rather odd

#### Basic operators

| Symbol        | What it does   |
|:--------------|:---------------|
| `+`           |Addition        | 
| `-`           |Subtraction     |
| `*`           |Multiplication  | 
| `/`           |Divison         |

Addition and Subtraction are pretty self-explanitory, though do remember to use * and / for mutiplication and division.

#### Other operators
I am not going to list every operator but I will go through some of the more used ones.

`%` (Modulo) - Finds the remainder

For example:

```python
print(7%2)
```

```
1
```

`//` (Floor division) - divides, but if  i is not a whole number the number rounds down

For example:

```python
print(7//2)
```

```
3
```

`**` (Exponents) - multiplies by itself a cerain amount of times

For example:

```python
print(7**2)
```

```
49
```

### Math Library
Though I as an Australian will not call it "Math", though I have to deal with such when I code.

The math library is a library with a heap of mathematical functions, though we are getting of ourselves.

If you do want to explore further into <a target="_blank" href="https://docs.python.org/2/library/math.html">Math functions</a> go to the Python documentation
<div class="message2">In general if you want to delve deeper in Python go to the documentation</div>

### Conclusion
Great Job! You have learnt how to use mathematical operators in Python! If you have any question you can <a action="mailto:hi@pynapple.codes">Send me an email</a>. Next week we will be talking about variables, and input. 

<div class="message">Sorry the first few have been extremely short, now that I have a schedule I can post every week. Also the next few will have a lot more to cover.</div>



---
marp: true
theme: default
class: lead
paginate: true
---

<!-- headingDivider: 1 -->
<!-- backgroundColor: black -->
<!-- class: invert -->

# Intro to Python

## Variables, Data Types, Operators, and Input/Output

# Getting started

Today we will be using **Google Colab!**

![bg right:50% contain](./deploying-textclassification-colab-activelearning.webp)

## Please click the link in chat

*(Pssst!  Will!  Put the [link](https://colab.research.google.com/drive/1LlL6-4H3uZYC7e0uz9aRmOHhpI1_J3Fj?usp=sharing) in the chat!)*

Then click file -> "Open in playground mode"

<!-- Give me a thumbs up when you're ready to move on! -->

# Google Colab

Colab runs Jupyter Notebooks, a type of file that combines text and Python code in blocks called cells. Some blocks are text just for reading, and some have code, which can be run.

- Tips for Windows:
  - `🪟` + `⬅️` or `➡️` to put your windows side-by-side
  - `Alt+Tab` to switch between windows
  - `Ctrl+Tab` and `Ctrl+Shift+Tab` to go back and forth between tabs

<!-- You'll need to switch back and forth between Teams and your browser. I've indicated the slide numbers beside each section of the notebook to help you keep track of where we are in the lesson. I also want you to disable AI suggestions by going to settings (gear icon at the top right) and clicking AI Assistance, then uncheck "show AI-powered inline completions" if it's checked. -->

# Hello World

Keeping with tradition we'll start by printing "Hello, World!" to the console.

```python
print("Hello, World!")
```

- Run it by clicking the little play button: ![play_btn](./play_btn.png)
- or typing `Shift + Enter`
- Try changing the words between the double-quotes and run it again!

<!-- Give me a thumbs up when you're ready! -->

<!-- Notes: What is this print() thing?

This is one of many built-in "functions" available in Python.  In describing this line, one would say that we are "calling the print function and passing in the variable 'a'." Don't worry for now if that's too much to remember!

A function is kind of a mini-program. Soon you'll be writing your own functions, but we will only be using or "calling" them for now. -->

# Variables

We can tell the computer to "remember" something using variables.

Run the cell below:

```python
name = "Alice"
age = 30
print("Hello,", name)
print("You are", age, "years old.")
```

# Naming Variables

In lines 1 and 2 we are "assigning" a value to variables. You can name a variable whatever you want, but it should describe what it stores, just like labeling moving boxes!

![bg right:40% contain](./boxes-2.jpg)

# Another way to print variables

If you put a variable on the last line of a code cell, it will print the value of that variable.

## For example

```python
name
```

<!-- run it and tell me what you got! -->

# More on Variables

```python
age = 30
```

- The `=` in the above statement is called the assignment operator.
- Unlike in Math, the order matters and the variable always goes on the left; for example, this will give you a syntax error:

```python
30 = name
```

<!-- Run the code above and give me a thumbs up! -->

# Variables: Try it some more

In the empty cell below, create a *new* variable and assign a value to it, then print the value of your variable. For example:

```python
today = "Monday"
print(today) # this would print 'Monday'
```

```python
# Put your code below

```

<!-- Give me a thumbs up when you're ready! -->

# More on Variable Names in Python

- Variable names must begin with a letter or an underscore (`_`).

- There are some *conventions* you should follow:
  - If your name has a space in it replace the space with an underscore.
  - Only use lowercase letters. Uppercase names are reserved for classes, which we'll get to later.

# Data Types

Python has strings, integers, floats, and booleans.

To find the type of something, you can use the `type()` function

```python
x = 10   # integer
y = 3.14  # float
z = "Python" # string
a = True  # boolean

type(a)
```

<!-- Run the code above and tell me what you got! -->

# Data Types: Try It

Check the type of the variable you created previously, using `type()`. Alternatively, you can make a new variable if you like.

## **Example**

```python
dog = "Fido"
type(dog)
```

(This example would print <class 'str'> and 'str' is short for string)

```python
# Put your code below

```

<!-- Run the code above and give me a thumbs up! -->

# Operators

# Operators (Slide 13)

We can do arithmetic with these operators:

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`

Run this code block:

```python
result = 10 + 5
result
```

<!-- Run the code above and give me a thumbs up! -->

# Operators: Try it

- In the cell below, do the following:
  - store the result of 5 + 3 in a variable called `sum`
  - store the result of 5 - 3 in a variable called `difference`
  - store the result of 7 x 2 in a variable called `product`
  - store the result of 6 / 2 in a variable called `quotient`

```python
# Put your code below

```

# Input and Output

We can interact with the user by taking input and displaying output.

```python
name = input("What is your name? ")
print("Hello,", name)
```

<!-- Run the code above and give me a thumbs up! -->

# Input and Output: Try it

Ask the user for their name and then print a greeting using their name.

```python
# Put your code below
```

# That's it for now

Remember: the best way to learn Python is by playing with it!

Practice and experiment whenever you can!

![bg right:40% contain](./porky_pig.jpg)
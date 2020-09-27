# Python Turtle

In this lab you will learn:

- How to get your turtle through a maze!

# Introduction

Let's practice using the Turtle.  Type the following command in the Terminal:

```
$ python
``` 

If all goes well, you should reach Python Interactive Mode

```
Python 3.7.6 (default, Jan 14 2020, 00:31:24) 
[GCC 7.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
``` 

## import turtle

Let's import the turtle module and show the turtle on our CS50 Lab Desktop

```
>>> import turtle
>>> turtle.showturtle()
``` 

If all goes well, your CS50 Lab Desktop should look like this:

![Desktop](https://raw.githubusercontent.com/profpy/id1400/master/lecture2/turtle1.PNG)

### forward

Move the turtle forward by the specified **distance**, in the direction the turtle is headed.

```
turtle.forward(distance)
``` 

or

```
turtle.fd(distance)
``` 

### backward

Move the turtle backward by **distance**, opposite to the direction the turtle is headed.

```
turtle.backward(distance)
``` 
or
```
turtle.bk(distance)
``` 

### left

Turn the turtle by the specified **degrees** left.

```
turtle.left(degrees)
``` 

### right

Turn the turtle by the specified **degrees** right.

```
turtle.right(degrees)
``` 

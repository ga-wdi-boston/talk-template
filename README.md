[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Python Intoduction with Micaela

## Preparation and Tips

1.  Fork and clone this repository.
1.  Take notes as needed.
1.  Do not be hesitate to ask questions, this is a new language!

## Objectives

By the end of this, developers should be able to:

-   Explain what Python is.
-   Understand the ways that Python is used.
-   Compare Ruby to Python.
-   Name the framework that Python uses.
-   Understand how to start the Python interpreter.
-   Write and interpret a few basics in Python.

## What is Python?

Python is a multi-paradigm programming language - object-oriented programming and structured programming are fully supported, and many of the language features support functional programming.

## What is Python used for?

Because it is a general purpose language, Python can be used for many different things, including small, large, online, or offline projects.

Python is commonly used in -
-   Web Development
-   Data Analysis
-   Machine Learning
-   Computer Vision
-   Internet of Things With Raspberry Pi
-   Game Development
-   Web Scraping
-   Rapid Prototyping

A few mordern technologies that use Python -
-   Instagram
-   Google
-   Pinterest

Python also has object oriented access to several different database systems, including SQLAlchemy and SQLObject.

Here is a list of useful Modules, Packages, and Libraries for Python - [](https://wiki.python.org/moin/UsefulModules#Useful_Modules.2C_Packages_and_Libraries)]

## Python vs Ruby

### Python
-   Language - Is direct
-   Pros - Very easy to learn, diverse community with big ties to Linux and academia
-   Cons - Often very explicit and inelegant to read
-   Web Framework - Django
-   Community - Very stable and diverse, but innovates slower

```python
print "Hello World"
```

### Ruby
-   Language - Is magical ~*~
-   Pros - Tons of out of the box features for web development, quick to embrace new things
-   Cons - Can be very hard to debug at times
-   Web Framework - Ruby on Rails
-   Community - Innovates quicker but causes more things to break and is very web focused

```ruby
puts "Hello World"
```

These two languages look very similar when being read, yet have distinct differences.
Both languages use a hash (#) to write comments within the code.
Ruby requires "end" or "}" to close all of its scopes while Python uses white-space only.

### Lets compare some simple code!

Both languages can set variables in the same way -
Just so we can get a taste of how these two languages are different (and similar), lets see if we can reverse the words in this string:

```
sentence = "backwards is sentence This"
```

First, lets solve it in Ruby -
```ruby
sentence.split.reverse.join ' '
```

Now, let's check out Python -
```python
" ".join(reversed(sentence.split()))
```

Let's share thoughts on the similarities and differences.

## Starting Out With Python

We have -
-   Variables - store values for later use. You can reassign variables in Python.
-   Data Types - such as numbers, booleans, and strings (you can create strings with double, single quotes, or str(examplestring)).
-   Arithmetic Operations - including +, -, *, /, **, and %. You can incorporate other data types in mathematics operations when it comes to Python. For example, you could multiply a string by a number.
-   Basic String Methods - len(), lower(), upper(), str()
-   Comparators - Equal to ( == ), not equal to ( != ), less than ( < ), less than or equal to ( <= ), greater than ( > ), greater than or equal to ( >= ).
-   Whitespace - seperates statements in Python.
-   Comments - Initiated with a hash, can be used to make code easier to read. If you want to create a multi-line comment, you can include a whole block in a set of tripple quoation marks.


## Demonstration/Code-Along

Feel free to code along in your terminal while I go over a few of the basics above. Type "python" to start. If you would like additional info about what the Python interpreter can do, just type "help". If you wish to exit python, type "quit()".

Next - Let's show a little bit of source control using Python. This is a little more advanced than the basics that we are have covered, but some of this might look familiar to you. Let's try it out! Take note of the whitespace, indentation, and the 'if, elif, else' statement. What do you expect to happen when we run this code?

```python
def classroom():
    print "It is 9:00 AM!"
    print "Do you enter the classroom on the left or go straight to get a last minute cup of coffee?"
    answer = raw_input("Type left or straight and hit 'Enter'.").lower()
    if answer == "left" or answer == "l":
        print "You are on time! Good Job!"
    elif answer == "straight" or answer == "s":
        print "LATELATELATELATE"
    else:
        print "Why didn't you pick anything? Let's try again."
        classroom()

classroom()
```

## Lab (Optional)

Practice setting and reassigning variables, using different string methods, comparators, and arithmetic equations with proper syntax in Python.

Bonus - Build your own version of the source control function from the demonstration. Get creative with it!

## Additional Resources

-   Code Academy - Python - [](https://www.codecademy.com/courses/python-beginner)
-   Docs - [](https://docs.python.org/3/)
-   [](https://www.python.org/)
-   Codewars is helpful with learning Python.

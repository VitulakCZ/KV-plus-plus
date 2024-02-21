# KV++
<<<<<<< HEAD
## Nejlepší jazyk VŠECH DOB!
=======
# The best programming language EVER!
## Basic information

KV++ is an interpreted language written in Python and higly inspired by [CodePulse](https://github.com/davidcallanan/py-myopl-code) with new features and modifications you will really like.  

## Getting started

To get started, install [Python](https://www.python.org/), clone this repo, navigate there and run `python3 shell.py`.  
You should be greeted with a KV++ shell.  

## Features
### Hello world

Hello world program looks something like this:  
`zabijuteln("Hello, world!")`
### Variables

You declare variables with `dej` keyword:  
`dej x = 1`  
You change also change them with the `dej` keyword:  
`dej x = 1`  
`dej x = 2`  
`zabijuteln(x)`  
`# prints "2"`  

They are dynamic meaning they can hold any type.
### Input (KV++ Unique Features!)

There are two ways of dealing with input:  
#### Use google(bool argument) function to get a string

If you want to get a string, this is the way to do it.  
If you pass 0, it will behave like a normal input:  

`dej x = google(0)`  
`zabijuteln(x)`  
`# prints whatever the user has typed`  


In KV++ however, there is no way of comparing strings to each other  

`opravdu str1 == str2`: Illegal operation  

To be able to bypass that, you can pass 1 to the function  
and it will now return:
* pi if there is more then one character
* ASCII representation of the character (eg. "A" is 65)  

`dej x = google(1)`  
`opravdu x == 65 HEIL`  
`    zabijuteln("You wrote A")`
#### Use indianscammer(bool argument) function to get an int
>>>>>>> 88e1e21 (Update README)

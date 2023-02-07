<p align="center">
  <img src="./python-logo-generic.svg" />
</p>

# Introduction
Python is a high-level, general-purpose programming language. It mostly uses English keywords and elegant syntax that makes the language easy to read and understand. It can run on any OS (Linux, Unix, Mac OS X, Windows and even Android and IOS).

Rather than building all of its functionality into its core, Python was designed to be highly extensible via modules. This compact modularity has made it particularly popular as a means of adding programmable interfaces to existing applications.

It is FREE 🥳.
<br>
It doesn't cost anything to download and use. It can also be freely modified and re-distributed [open-source license](http://www.python.org/psf/license/).

# Main Features
## Data Typing
Python has typed objects but untyped variable names which means that the variable can store a value of any data type and the type of the value stored in the variable can be changed at runtime.

Here are few examples,

```python
my_variable = 10
print("1st assignment: ", type(my_variable))

my_variable = 10.54
print("2nd assignment: ", type(my_variable))

my_variable = "Test"
print("3rd assignment: ", type(my_variable))

my_variable = ()
print("4th assignment: ", type(my_variable))

my_variable = {}
print("5th assignment: ", type(my_variable))
```

Output,

```
1st assignment:  <class 'int'>
2nd assignment:  <class 'float'>
3rd assignment:  <class 'str'>
4th assignment:  <class 'tuple'>
5th assignment:  <class 'dict'>
```

## Object-Oriented
Python supports object-oriented programming with classes and multiple inheritances. The `class` statement, which executes a block of code and attaches its local namespace to a class, for use in object-oriented programming

## Memory Management
Puython uses a combination of reference counting and a cycle-detecting garbage collector for memory management. This automatic memory management frees you from having to manually allocate and free memory in your code.

## Exception Handling
Errors detected during execution are called exceptions and they are not aways fatal. Python has a fewer syntactic exception. It makes the error handling cleaner. <br>
The programers can write their own user-defined exceptions derived from the `Exception` class. Most exceptions are defined with names that end in `Error`, similar to the naming of the standard exceptions. Many standard modules define their own exceptions to report errors that may occur in functions they define.

## Predefined Clean-up Actions
Some objects define standard clean-up actions to be undertaken when the object is no longer needed. The `with` statement clarifies code to ensure that clean-up code is executed when the object goes out of scope. 
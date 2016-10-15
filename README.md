# learn-python
# Learn Programming in Python
### LSESU Applicable Maths Society

#### Taught by Tom Sherborne and Pavlos Charalambides

This is an an introductory course to the Python programming language. The objective of this course is to get you started building applications with an easy to learn and popular programming language. 

We'll be taking you through the basics of how to write code on your own laptop, as well as how you can use Python for trading, pricing and financial analysis. 

No prior knowledge of Python or programming is assumed and you can use any computer for this course, it is not recommended to use an iPad or device running a mobile operating system.

[Give It a Go talk](https://docs.google.com/presentation/u/1/d/1FHhpGavkM2se9Wfj_FkO1n-plpa4-wDqUkBz-9Ui_MQ)

## Setup Instructions (Mac)
### Installing

##### Downloading Python
For this class we will be using the [Anaconda version](https://www.continuum.io/downloads) of Python and [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html). Install __Python 3.5__ and Jupyter by following the instructions [here](https://www.continuum.io/downloads), select the 64 bit installation option.

Apple computers come with a version of Python installed already, but this is the old Python 2.7 and installing **Python 3.5** allows you to use the most up to date features of the language.

After installing Python, you can test if the installation was successful by opening Terminal and typing this command and hitting Enter.
```
python3 --version
```
Now you should see something like:
```
Python 3.5.2 :: Continuum Analytics, Inc.
```
Which tells you that Python is installed. If you don't see this, then try restarting your computer and trying again.
When this is completed successfully, run each of these commands one by one in Terminal. 
```
python3 -m pip install ipykernel
python3 -m ipykernel install --user
```

### Opening the lessons
Create a folder on your Desktop called `learn-python` to keep all of the lesson files in. This isn't required and you can keep a folder of each lesson somewhere else on your computer but this tutorial will assume that you have done this step from now onwards.

Each lesson is a Jupyter Notebok `.ipynb` file, this is an interactive environment to test and run Python code line by line, To open the lesson file, open Terminal and run the following commands:

```
cd ~/Desktop/learn-python
jupyter notebook
```
The Jupyter application will now activate and your default browser will now open with a screen which looks like this:

![Jupyter Opening Screen](images/jupyter_launch.png)

You can now click on the lesson you want to open and start writing Python. To close the Jupyter Notebook application return from your browser to Terminal and type Ctrl+C.

## Setup Instructions (Windows)
### Installing

For this class we will be using the [Anaconda version](https://www.continuum.io/downloads) of Python and [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html). Install __Python 3.5__ and Jupyter by following the instructions [here](https://www.continuum.io/downloads). Most modern Windows machines are 64 bit, but you can check which version you need [by clicking here](https://support.microsoft.com/en-gb/kb/827218)

Most modern Windows computers will have installed both Command Prompt and PowerShell for executing commands, either can be used for the instructions below. After installing Python, you can test if the installation was successful by opening Command Prompt/PowerShell and typing this command and hitting Enter.
```
python --version
```
Now you should see something like:
```
Python 3.5.2 :: Anaconda 4.2.0 (64-bit)
```
Which tells you that Python is installed. If you don't see this, then try restarting your computer and trying again.
When this is completed successfully, run each of these commands one by one in Command Prompt/PowerSHell. 
```
python -m pip install ipykernel
python -m ipykernel install --user
```

### Opening the lessons

Create a folder on your Desktop called `learn-python` to keep all of the lesson files in. This isn't required and you can keep a folder of each lesson somewhere else on your computer but this tutorial will assume that you have done this step from now onwards.

Each lesson is a Jupyter Notebok `.ipynb` file, this is an interactive environment to test and run Python code line by line, To open the lesson file, open Terminal and run the following commands:

```
cd Desktop/learn-python
jupyter notebook
```
The Jupyter application will now activate and your default browser will now open with a screen similar to the image above for Jupyter on Mac.

You can now click on the lesson you want to open and start writing Python. To close the Jupyter Notebook application return from your browser to Command Prompt/PowerShell and type Ctrl+C.

## Writing your own code (Sublime/PyCharm)

Jupyter is a great learning environment for starting with Python and executing small blocks of code. However, when you come to write a whole programme it can be more useful to use a code editor or an IDE (Integrated Development Environment). Writing code in an editor can perform faster and make tasks such as reading user input simpler. 

Two popular options for editors for Python are:

1. [Sublime Text](https://www.sublimetext.com/)
	This is a basic and fast editor which you can both write and run Python in. Sublime has a basic debugger to troubleshoot code issues, and an online community developing plugins to enhance your workflow. I use Sublime and Terminal when writing Python.

2. [Jetbrains PyCharm](https://www.jetbrains.com/pycharm/)
	This is a powerful IDE for Python development, and is free for students if they sign up with their .ac.uk email address. PyCharm has many extra features which can be very helpful as a beginner, but you will need to spend time learning how to use PyCharm properly to get the most out of the IDE.

### Course Structure
1. Getting setup, variables, loops and logic
2. Objects and functions, using libraries
3. Strings, indexing, iterating, reading files, comprehensions
4. Context managers, tuples and dicts, advanced comprehensions
5. Classes and inheritance, OOP structure in Python, magic methods
6. Data manipulation with Numpy and Pandas
7. Data viz with Matplotlib
8. Project lessons
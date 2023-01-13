# Detailed schedule and resources

## Class 1

The textbook is called *What Can Be Computed?*, which we abbreviate as
    *WCBC*.
      
Today we will go through the syllabus and an overview of the course,
corresponding to WCBC Chapter 1.

Today's PowerPoint: [01-intro.pptx](class01/01-intro.pptx).
  
If there's time, we will try to run and edit some Python programs
  using IDLE. Key points:

* Always use Version 3.x of Python for this course
* You can [download Python 3](https://www.python.org/downloads/) and
    install it on your own laptop etc.
* Python is also available on all department iMacs in Tome:
  - use the search functionality (top right of the desktop) to open
      IDLE with Version 3.x of Python
  - you can ignore any warnings about the version of Tcl/Tk

Another option is to use an online Python environment such
as [https://repl.it/new/python3](https://repl.it/new/python3). Here
  is some code to paste in and experiment with:
```	
def containsGAGA(inString): 
    if 'GAGA' in inString: 
        return 'yes' 
    else: 
        return 'no' 
```

Here's another one:
```
def multiply(inString): 
    (M1, M2) = inString.split()
    product = int(M1) * int(M2) 
    return str(product)
```

---- Last modified: Fri Jan 13 15:02:54 UTC 2023 by jmac.

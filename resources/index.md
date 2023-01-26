# Detailed schedule and resources

<!-- ## Class 3 -->

<!-- Required reading: WCBC Chapter 3. -->

<!-- Handout for today: [class3-handout.pdf](class03/class3-handout.pdf). If you have easy access to a printer, print this out before class, but that is not essential. -->

<!-- Today's warm-up exercise: [03-warmup.docx](class03/03-warmup.docx) -->

<!-- Today's PowerPoint: [03-impossible-programs.pptx](class03/03-impossible-programs.pptx). -->

## Class 2

Required reading: Chapters 1 and 2 of WCBC.

Today's PowerPoint: [02-computer-programs.pptx](class02/02-computer-programs.pptx).

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

---- Last modified: Thu Jan 26 01:51:32 UTC 2023 by jmac.

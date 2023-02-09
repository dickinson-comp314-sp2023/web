# Detailed schedule and resources

## Class 6

Required reading: WCBC Chapter 6.

Today's PowerPoint: [06-universal-programs.pptx](class06/06-universal-programs.pptx).

Really nice online [cellular automaton simulator](https://devinacker.github.io/celldemo/).

Optional minilab (ungraded, but important and fun):

*   Download the [Universal Turing machine](class06/tu.jff) of Lucas and Jarvis (see also their [explanatory webpage](http://www.itss.brockport.edu/~jlucas/jarvis/JFLAP/examples/e2/pg0.html) if you're interested).
*   Create a LastBtoA machine, similar to LastTtoA from the previous class, but using only the alphabet `a,b` (and blanks). If this isn't clear, you can also use the provided version of [LastBtoA](class06/LastBtoA.jff). We will use LastBtoA as an input to the Lucas and Jarvis Universal Turing machine.
*   Encode LastBtoA so that it is suitable for input to the Lucas and Jarvis Universal Turing machine. An [explanation of the encoding](class06/example-encoding-of-turing-machine.pdf) is provided. Lucas and Jarvis provide [another explanation](http://www.itss.brockport.edu/~jlucas/jarvis/JFLAP/examples/e2/pg1.html) on their website.
*   Test your encoding using the Universal Turing machine and an appropriate input string. In JFLAP, the best way to run this test is to first save your input to a text file, then use the "multiple inputs (transducer)" option from the "input" menu.



## Class 5

Required reading: WCBC Chapter 5.

To download JFLAP, follow the instructions at [jflap.org](http://jflap.org/getjflap.html) (you will be asked to fill out a short form). The best version for this course is JFLAP7.1.jar from Jul 27, 2018.

**If the JFLAP website is down you can get [JFLAP on Moodle](https://lms.dickinson.edu/mod/resource/view.php?id=1172511) instead**

**If JFLAP won't run when you click on it, open a terminal, navigate to the directory where you have saved the file `JFLAP7.1.jar`, then enter the command**
```
java -jar JFLAP7.1.jar
```
(Of course, you need to have Java installed on your computer for this to work.)

Minilab (ungraded): using JFLAP,

*   experiment with [binary-incrementer.jff](binary-incrementer.jff)
*   Create and test the basic version of LastTtoA (fig 5.3)
*   Create and test the abbreviated version of LastTtoA (fig 5.6)
*   Create and test a machine that processes genetic strings, changing every "c" to a "g" and every "g" to a "c"
*   Optional extras: Create a machine that accepts any string of length 10 or more that also contains an "a".

Today's PowerPoint: [05-turing-machines.pptx](class05/05-turing-machines.pptx).

## Class 4

Required reading: WCBC Chapter 4.

Today's warm-up exercise: [04-warmup.docx](class04/04-warmup.docx)

Today's PowerPoint: [04-computational-problems.pptx](class04/04-computational-problems.pptx).

Programs for experimenting with ESS and DESS: [switchAndConcat.py](class04/switchAndConcat.py), [switchAndConcat1Param.py](class04/switchAndConcat1Param.py). (Remember to move these into your `wcbc-programs-v1.1` folder.)

## Class 3

Required reading: WCBC Chapter 3.

Handout for today: [class3-handout.pdf](class03/class3-handout.pdf).

Today's warm-up exercise: [03-warmup.docx](class03/03-warmup.docx)

Today's PowerPoint: [03-impossible-programs.pptx](class03/03-impossible-programs.pptx).

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

---- Last modified: Thu Feb 09 03:28:05 UTC 2023 by jmac.

## SDSS Computing Studies Python Assignment
### Assignment #009c TKinter Checkbuttons

Objectives:
* Retrieve and set values using the tkinter checkbutton widget

Buttons, Labels and Entry widgets are useful for adding data to a GUI, but another important
Widget is the Checkbutton.

The checkbutton is the box that has two states, checked and unchecked.  In Python, we store
these states as an IntVar() or integer value that is either 1 or 0.  See Example1.py for an
example of a checkbutton is instantiated and the data is read from it.

Note that when retrieving the value of the Checkbutton, we .get() from the variable that is
bound to it, not from the button itself.

### 1 Task (12 marks)

##### Task 1
Create a binary converter.
Recall that binary is a system of counting based on powers of 2.
00000001 = 1
00000010 = 2
00001110 = 14

Create a converter that will convert binary to decimal or decimal to
binary using the interface shown in task1.png.  Use the shell that
has been started in task1.py
(12 points) 


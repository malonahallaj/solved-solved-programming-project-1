Download Link: https://assignmentchef.com/product/solved-solved-programming-project-1
<br>
This programming project will use the raw_input and print functions along with some simple mathematics for conversion. The important part of the project is to learn the skills needed to access the class web site to download a project description, create a new program in Python and finally to hand it in. We are going to estimate the length of time that passes for astronauts as they travel at near light speeds.

You may remember that time passes more slowly for the astronauts on ship than those on earth as the ship approaches the speed of light. You may also remember that the mass of the ship also increases as it approaches light speed (which, therefore, is an estimate of how much more energy much be expended as you approach light speed).

You may remember that Einstein wrote a simple equation that provides a factor indicating the change in time and mass based on speed, which is: where v is velocity and c is the velocity of the speed of light, which is well approximated at 299,792,458 meters/second.

The factor calculated is how much time is reduced by and how much mass is increased by. For example, at 149,896,229 meters per second (half the speed of light) the factor is 1.1547005383792517. Time’s passage is reduced by the factor (division) and the mass is increased (multiplication). Program Specifications Your program will prompt the user for a floating point number representing percentage of the speed of light your ship will travel. Your program then prints the following information:

• the weight of the ship. Assume the ship weighs 70,000 kilograms, the weight of the empty space shuttle orbiter, when at rest.

• The times the astronauts experience for trips to: o Alpha Centauri: 4.3 Light Years o Barnard’s Star: 6.0 Light Years o Betelgeuse (in the Milky Way): 309 Light Years o Andromeda Galaxy (closest galaxy): 2,000,000 Light Years Deliverables proj01.py — your source code solution (remember to include your section, the date, project number and comments).

1. Please be sure to use the specified file name, i.e. “proj01.py”

2. Save a copy of your file in your CSE account disk space (H drive on CSE computers).

3. You will electronically submit a copy of the file using the “handin” program: http://www.cse.msu.edu/handin/webclient Assignment Notes: To input the numbers it is necessary to use the raw_input function. The raw_input function takes a string, a sequence of characters between quotes, as a prompt to print to the user. It then waits until the user types a response, terminated by the user typing the Enter key. A string, again as a sequence of characters, is returned. The returned string must be converted to a number. In this assignment we are strictly working with floating point numbers, a string is converted to a float using the float function.

The float function takes as an argument a single string and returns the floating point number the string represents. A typical interaction would be something like: numStr = raw_input(‘Please enter a number: ‘) floatVar = float(numStr) print is a command that will print on the output window any combination of variables, values and strings. Each item to be printed must be separated from other items by a comma.

All the items will be printed together, followed by a new line. For example: billsFloat = 123.456 print ‘The number ’,billsFloat,‘ times two is ’, billsFloat*2 This command has 4 items to print: a string (‘The number ’), the value in the variable billsFloat (123.456), another string (‘ times two is ’) and the result of an expression (246.912). It will print: The number 123.456 times two is 246.912 Look at the program numInput in the 231 Examples directory as an example of using raw_input, print and float (also int for integer numbers).

Once converted to numbers, the operations on these numbers are, respectively: + (sum), – (difference), * (product), / (division) and % (remainder). The last two deserve special comment. In Python, if an integer is divided by another integer, the result is an integer. Thus the result of 6/4 is 1 (not 1.5). That is, the “/” operation results in the integer quotient.

The result of 6%4 is the integer remainder of the division, thus 2 (6 divided by 4 is 1 with a remainder of 2). Play around with the quotient and remainder operators in the Python shell window until you get comfortable with how it works. To clarify the problem specifications, we provide at the end of this document a snapshot of interaction with the already written program. Getting Started

1. Using IDLE create a new program.

2. If you are in a CSE lab, select the H: drive as the location to store your file

3. Save the name of the project: proj01.py

4. Using the example from numberInput.py, write the code. Track down any errors (shouldn’t be any at first).

5. Run the program

6. Use the handin web site to hand in the program (to make sure you can do it)

7. Edit the program

8. Now you enter a cycle of edit-run to incrementally develop your program.

9. Use handin to hand in your final version. Be sure to save a copy of your completed program in your CSE file space (H: drive on the lab machines) before the deadline by which the program needs to be handed in. If you write your program at home and turn it in from home, you will need to copy it over before the deadline.

In case of problems with electronic submission, an archived copy on the CSE disk is the only acceptable evidence of completion. Questions for you to consider (not hand in)

1. What happens if you try to go faster than the speed of light? 2. What happens when you enter a letter instead of a number at the prompt? Sample Interaction
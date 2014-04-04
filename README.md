ECE281_CE4
===========

##CE4

####Program A
a)  Simple Memory Manipulation: Write a program that stores the value $9 in location $B0, $8 in $C4 and $B in $CB. (Target program end: $11)
My version of the program worked. I met the target end for this program

####Program B
b)  Mathematics: Write a program that retrieves a value from location $B0, doubles it, and subtracts 4.  The result should be output to Port 2. You will need to place a positive test value in this location prior to running the program.  Although RAM is volatile and you normally cannot directly change values in it without having a program do it, you can in this simulation by checking “Allowed RAM values to be edited” in the Programming Wizard.  (Target program end: $0C)
My version of the program worked.  I doubled the number by rotating right 3 times.  I met the target end for this program

####Program C
c)  Loops: Write a program that starts by reading what is on Input Port 3 and then displaying that on Output Port 0.  One less than that should then display on Port 1 and one less than what is on Port 1 will display on Port 2.  The program then decrements what is on Port 0, then decrements what is on Port 1, then decrements what is on Port 2.  This process is continued in an infinite loop (i.e. If Input Port 3 contains a ‘2’ , Ports 0-2 will show 2,1,0, respectively.  The 2, 1, 0 will then change to 1,0,F, then 0, F, E, and so on). (Target program end: $10)
My version of the program worked.  I did not meet the target end for this program.

#### Debugging


#### Room for Prism program improval
The program should have a "do you really wish to exit" option before closing program because I accidentally closed the prism program on myself while writing the program 3 times.  I know it is mostly stupidity on my part, but it is also very frustrating

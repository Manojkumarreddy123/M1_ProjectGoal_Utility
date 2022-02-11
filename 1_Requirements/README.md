Digital stopwatch project 

Reqirements :
Introduction:
keyboardhit() function  :This function simply stands for keyboard hit.
After pressing a key it generates a signal and returns a non zero integer. 
In this, there are 4 loops, 1st loop for hours, 2nd for minutes, 3rd for seconds and 4th loop for maintaining the speed of seconds(3 loop).
After running this program it wait for a keyboard start(s) key to be pressed and when key is pressed, it generates a signal.
For storing a keyboard key there is a variable(c), if c is equal to p key then it calls the wait function. 
The thread is running in the background and we are waiting for the start key to be pressed. 
After pressing s key, the thread again jumps to thread_join function, if r key is pressed, then it jumps into reset label and all the loops are again starts with zeros,
if s key is pressed it jumps into start label and if e key is pressed it calls the exit() function and program gets terminated.
To execute the program we use following command :

gcc -pthread stopwatch.c -o stopwatch./stopwatch





Input:
Press a key :
s -> start
e -> exit
r -> reset
p -> pause




Low Level Reqirements :

LLR1	In the first the stage the user need to select the options .

LLR2	The options are Press a key :
s -> start
e -> exit
r -> reset
p -> pause

LLR3  After pressing any key which the user wants after running this program it wait for a keyboard start(s) key to be pressed and when key is pressed, it generates a signal.

	

High Level Reqirements :

HLR01	User should be able to use this utility

HLR02	User shall be able to use all the key which is used to implement the program.

HLR03	User should able to press the input keys correctly so that the required command can be followed. Those input keys are :

Input:
Press a key :
s -> start
e -> exit
r -> reset
p -> pause


	
4W's and 1'H

Who:
For users who want to use the stopwatch to count the time.

What:
Users can easily count time in Hours, Minutes and Seconds.

When:
It can be used to when the users needs stopwatch.

Where:
We can use this application ant where by opening this application and by pressing the correct input key.

How:
We can use this application ant where by opening this application and by pressing the correct input key.

Input:
Press a key :
s -> start
e -> exit
r -> reset
p -> pause




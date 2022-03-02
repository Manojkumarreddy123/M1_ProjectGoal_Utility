# M1_ProjectGoal_Utility
# PROJECT
# Digital stopwatch project 

Introduction:
keyboardhit() function  :This function simply stands for keyboard hit. After pressing a key it generates a signal and returns a non zero integer. In this, there are 4 loops, 1st loop for hours, 2nd for minutes, 3rd for seconds and 4th loop for maintaining the speed of seconds(3 loop). After running this program it wait for a keyboard start(s) key to be pressed and when key is pressed, it generates a signal. For storing a keyboard key there is a variable(c), if c is equal to p key then it calls the wait function. The thread is running in the background and we are waiting for the start key to be pressed. After pressing s key, the thread again jumps to thread_join function, if r key is pressed, then it jumps into reset label and all the loops are again starts with zeros, if s key is pressed it jumps into start label and if e key is pressed it calls the exit() function and program gets terminated.


To execute the program we use following command :
  
![image](https://user-images.githubusercontent.com/98941312/156295551-8199178f-73cf-4a52-828e-b9a3a0188899.png)







	

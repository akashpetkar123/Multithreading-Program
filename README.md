# Multithreading-Program
How to use multithreading in a program ?

This program will help you to understand how to utilize multithreading capabilities
This is an applet program which consist of three balls i.e three threads red, green, blue 
Three threads will move forward at a certain speeds i.e 
blue thread speed will be fast
green thread speed will be slow than blue thread
red thread speed will be slow than green thread

when we run the main program a thread get executed which we called it as the main thread.
The main thread is responsible for executing and completing the execution of all the threads which is under that thread

When main thread gets executed , then under that main thread three threads i.e(red,green,blue) threads are executed at a time
we used the synchonized block to handle the executing thread and complete the its excution and so on, until all the threads have
ompleted their execution.

when main thread starts then all threads i.e (red,green,blue) thread also gets executed at a time
we use the thread.sleep(int) to use to pause the executing thread for some time and give chance to some other thread for execution
achieve the total usage

when all threads starts then blue thread will go to a position and wait until red,green thread reaches to that position
this program will help to analysis how multithreadings works

The below link video will show how the program works:-
https://youtu.be/J71pTv0gWgc





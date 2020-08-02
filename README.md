# Service-Browser
This is a service browser that lets the user choose between three small programs, a small visual music player using MIDI packages and Swing, a dice rolling generator, and a program to get the day of the week of a specific date.  All of these were implemented using different packages that come with java, and also the RMI package for remote method invocation on a server.  Of course this program will just be ran on local host.

(Runs in Java 14, these commands are for MacOS users)
STEPS TO RUN THE PROGRAM:

1.) Extract all of the files to a new project directory.

2.) Open terminal and navigate to the src directory of the project and issue the command: % javac *.java\
    This command will compile all of the .java files into .class files which are runnable.
    
3.) Stay in the src directory in your terminal and issue the command: % rmiregistry\
    This command will generate a new stub file for the server
    
***IMPORTANT STEPS MAKE SURE YOU FOLLOW EXACT****\
4.) In a separate terminal navigate to the src directory again and issue the command: %rmiregistry\
    IT IS IMPORTANT TO LEAVE THIS RUNNING.  Just type the command, hit enter, and leave the terminal as is.
    
5.) In another separate terminal, navigate again to the src directory and issue the command: % java ServiceServerImpl\
    IT IS IMPORTANT TO LEAVE THIS RUNNING.  Just type the command, hit enter, and leave the terminal as is.
    
6.) Now you should be able to run the ServiceServerImpl in your IDE, this starts the server, so you must leave it running.

7.) Finally, run the ServiceBrowser and a new Java window should appear with the app fully functional.


#KEYLOGGER

Keylogger software is a good beginner-level cyber security project. A keylogger is software used to record every keystroke made by the user on their keyboard devices.



Steps:
  
1) Installing Required Libraries
Before we begin, we need to install a particular library, which we can do with  

The pip command: pip install pynput and pip install jsonlib.

pynput: This will help us read the keystrokes as the user types in stuff

JSON is a lightweight data-interchange format. It is often used for exchanging  data between a web server and user agent

2) Initialization:
      Set up the main GUI window.
      Initialize global variables for key logging
   
4) Event Capture:
      Start capturing key events when the "Start" button is pressed.  Log key press and release events
   
5) Data Logging: 
    Continuously update text and JSON log files with captured key events.
   
6) Stop Logging:
    Stop capturing key events when the "Stop" button is pressed.  Update the GUI status to indicate the keylogger is stopped!

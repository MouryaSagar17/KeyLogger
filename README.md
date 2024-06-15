  
Installing Required Libraries
Before we begin, we need to install a particular library, which we can do with  

The pip command: pip install pynput and pip install jsonlib.

pynput: This will help us read the keystrokes as the user types in stuff

JSON is a lightweight data-interchange format. It is often used for exchanging  data between a web server and user agent
Initialization:
      Set up the main GUI window.
      Initialize global variables for key logging
Event Capture:
      Start capturing key events when the "Start" button is pressed.  Log key press and release events
Data Logging: 
    Continuously update text and JSON log files with captured key events.
Stop Logging:
    Stop capturing key events when the "Stop" button is pressed.  Update the GUI status to indicate the keylogger is stopped!

    ![image](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/abbd518f-08e1-4894-8f5e-a40f83a72788)

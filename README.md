# KEYLOGGER



+ [Introduction](#Intro)
+ [Requirements](#Require) 
+ [Execution](#Execute)
+ [ Output ](#Output)

# Introduction <a name="Intro">
Keylogger software is a good beginner-level cyber security project. A keylogger is software used to record every keystroke made by the user on their keyboard devices.

# Requirements <a name="Require">
  
  1. Installing Required Libraries
     - Before we begin, we need to install a particular library, which we can do with
     -  The pip command:
           ``` cmd
             pip install pynput
           ```
           ![Screenshot 2024-06-14 173840](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/13e47590-a6d0-4663-b160-a6fccf01f3a2)

           ``` cmd
            pip install jsonlib.
           ```
          ![Screenshot 2024-06-14 173815](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/5e81346b-e2f1-45f1-966b-8fe5090dc177)

     -   ynput: This will help us read the keystrokes as the user types in stuff

**JSON is a lightweight data-interchange format. It is often used for exchanging  data between a web server and user agent**

# Execution <a name="Execute">

**1. Initialization:**
      - Set up the main GUI window.
      - Initialize global variables for key logging
        
   
**2. Event Capture:**
      Start capturing key events when the "Start" button is pressed.  Log key press and release events

   ![start](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/30e9eb67-56f1-4093-87e6-9f85c226a795)

   
**3. Data Logging:** 
    Continuously update text and JSON log files with captured key events.

![keystrokes](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/1e34399f-fc08-42f1-b2ff-f075358f37de)

   
**4. Stop Logging:**
    Stop capturing key events when the "Stop" button is pressed.  Update the GUI status to indicate the keylogger is stopped!
   
![stop](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/61058048-0743-4463-83e9-6493ef7d29b4)

# Output <a name="Output">
1. Successfully implemented a keylogger that captures keystrokes and records them into both text and JSON files.
2. Real-time keylogging with start and stop functionality controlled via a simple GUI.
3. The keylogger project demonstrated the capability to effectively capture and log keystrokes in real-time.
4. The GUI provided a user-friendly way to control the keylogger, making
5. it accessible and easy to use.
 
   # Emphasized the ethical use of keyloggers and the importance of implementing security measures to protect against malicious use
# Fnal Output
![Final Output](https://github.com/MouryaSagar17/KeyLogger/assets/143429477/c07451b7-a0c9-46b1-828b-ef149b5cdb86)



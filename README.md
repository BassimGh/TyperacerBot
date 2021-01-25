# TyperacerBot

#### A python script that takes a screenshot and types the text of that screenshot instantly. 

I made this fun to see how high of a score I can get on a **practice** typeracer race. **Please do not use this script in public typeracer races**

### How to use it?

1. Press an hold the middle mouse button and release to create a rectangle around the desired capture area on the screen
2. Press the number lock key and the script will type the text from the screen capture

### How does it work?

* Pynput captures the mouse actions and coordinates needed to assign screenshot coordinates
* Pyscreenshot uses those screen coordinates to capture an screenshot of the specified region
* Pytesseract converts the image to a string
* Pynput simulates key presses and types the string of text
* Time assigns a brief pause in between each key press to control typing speeds.

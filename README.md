# IDD-Fa18-Lab1: Blink!

**A lab report by John Q. Student**

## Part A. Set Up a Breadboard

<p align="center">
  <img src="Lab1_PartA.png" width="350" height="350">
</p>


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**

**Answer: Red and brown**
 
**b. What do you have to do to light your LED?**

**Answer: When connected the LED won’t immediately light, you must press the button to connect the circuit and light the LED.**


## Part C. Blink a LED using Arduino

### 1. Blink the on-board LED

**a. What line(s) of code do you need to change to make the LED blink (like, at all)?**

**Answer: You don’t actually need to change the example code to get the on board LED to blink, since it seems the “LED_BUILTIN” variable maps to pin 13. But if you wish you can replace “LED_BUILTIN” and get the same result.**

**b. What line(s) of code do you need to change to change the rate of blinking?**

**Answer: To change the blinking rate you only need to change the parameters of the delay() functions. This controls the pause length in-between the digitalWrites, which controls the signal outputted to the built in LED.**

**c. What circuit element would you want to add to protect the board and external LED?**

**Answer: To protect the board and external LED I would add a resistor. **
 
**d. At what delay can you no longer *perceive* the LED blinking? How can you prove to yourself that it is, in fact, still blinking?**

**Answer: I could no longer perceive the LED blinking when the delay parameter was set to 12ms. You can tell it's still blinking by using the multimeter to check the variance in voltage during the code execution.**

**e. Modify the code to make your LED blink your way. Save your new blink code to your lab 1 repository, with a link on the README.md.**

**Answer: I programmed my blinking LED to have a longer pause(5x longer) after being lit.**

### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[link to your video here; feel free to upload to youtube and just paste in a link here]


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**


## Part E. Fade an LED using Arduino

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

**b. What is analogWrite()? How is that different than digitalWrite()?**


## Part F. FRANKENLIGHT!!!

### 1. Take apart your electronic device, and draw a schematic of what is inside. 

**a. Is there computation in your device? Where is it? What do you think is happening inside the "computer?"**

**b. Are there sensors on your device? How do they work? How is the sensed information conveyed to other portions of the device?**

**c. How is the device powered? Is there any transformation or regulation of the power? How is that done? What voltages are used throughout the system?**

**d. Is information stored in your device? Where? How?**

### 2. Using your schematic, figure out where a good point would be to hijack your device and implant an LED.

**Describe what you did here.**

### 3. Build your light!

**Make a video showing off your Frankenlight.**

**Include any schematics or photos in your lab write-up.**

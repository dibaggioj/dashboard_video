# Gigabots Dashboard with Live Video

Gigabots Dashboard with Live Video Stream and Channel Activity

# About

This is for a Raspberry Pi with Pi Camera Module streaming MPEG1 video over a websocket, on top of Lego Mindstorm robot running The Gigabots Firmware (uses Big Bang). The robot can be remotely controlled in real-time and its live video stream can be viewed in this build of the web-based Gigabots Dashboard (uses Big Bang).

Version 2.0 Build 2

# Instructions for Use

Click on the 'Select Gigabot' drop-down menu in the navigation bar above the dashboard. This will display a list of the robots currently connected to the Big Bang channel for The Gigabots. Select a robot by clicking on a name. You will see the settings and data in your dashboard instantly update to those for this robot.

In the bottom right-hand corner of the dashboard, you will a 'Channel Activity' box. This shows everyone that's connected to the channel, with GitHub-style icons, and which bots users have selected. Because multiple user can control the same bot at the same time, it will also display live update regarding what users controlling the same bot as you are doing. From the 'Send a Message' box below that, you can send a short message to all users.

The controls are simple:

- You'll see the dashboard divided up into different motors. For each motor, you can flip which direction is actually forward or reverse using the checkbox 'Swap Directions.' You can adjust the speed between 0 and 700 degress of rotation per second, using the slider bar or using the '+' and '-' buttons for 50 degree/second increments. Holding down the 'Forward' or 'Reverse' buttons will cause the motor to rotate in one direction or the other.
	
- For more flexibility, the any of the motors can be combined into a motor gang, so that they can be controlled together. For example, this can facilitate driving in a straight line by combining two motors for wheels on both sides of a bot (with their directions orientated similarly) or turning on a spot by combining two motors for wheels (with their direcitons orientated opposite from one another).
	
- For ease of use when not on a touchscreen device, there are also some keyboard shortcuts for controlling motors and gangs, as follows:
 
	asdf

On the left-hand side of the dashboard, you will see a box displaying the name of your selected bot, its current battery level, and a button for pausing/resuming the dashhboard. Below that is data from various sensors available, which updates in realtime.

At the bottom of the dashboard, there is a read-eval-print-loop (REPL) / console-based text editor. You can use this to make calls with the Gigabots API (described further below). This is ideal for programming bot behaviors, as entire blocks of code can be written or placed in the editor and run.

# License

The MIT License (MIT)

Copyright (c) 2014 Big Bang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


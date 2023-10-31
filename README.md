# Generic-AT89C50-Board-Code
The objective of this project was to select a particular mode from 1 to 4 to direct the microcontroller to perform a set tasks coded in Assembly language. 
The tasks were as follows:

  Mode 1: 
Suppose a mobile robot moving with initial velocity Vo=4 and acceleration a=3. Determine distance covered by the robot after time t sec using 2nd equation of motion
Value of time should be taken from port 1. You need to display low byte of distance on Port 0 and high byte on Port 2 for exactly 2 seconds continuously. If value of distance exceeds 2 bytes set bit P3.2. (Ignore Remainder)

Mode 2:
In this mode you have to implement Fibonacci series (0,1,1,2,3,5,…). Take value of index from Port 1 (0 to 13) and display corresponding number in Fibonacci series on Port 2 for exactly 1.2 sec. Your program must run continuously until mode has been changed.

Mode 3:
In this mode, you need to read input from port 1 and program Port 2 to blink (from LSB to MSB,) and Port 0 to blink (from MSB to LSB),one pin at a time with frequency relative to the input.

Mode 4:
In this mode, you need to read input from Port 1 and blink LEDs of port 2 and Port 0 with frequency 3Hz and duty cycle relative to the input as following:
port 1 value : % duty cycle
00 : 0
128 : 50
255 : 100

Further details of the project may be found in the report

# Power-Curve-Calculator


Power Curve Displayer
Made by Jess Zarchi / 21S Team Captain
Code originally made for OGLLA

TO USE:
Firstly, config the motor and sensor setup to your needs
Make sure when you raise the arm, you get positive numbers.
Configure void runMotors( ) to your needs

Start code with the arm down. Then bring the arm up. Set
iMaxHeight equal to the max height your arm can mechanically go.

Open:
Robot > Debugger Windows > LCD
Robot > Debugger Windows > Debugger Stream

Select the speed you'd like to run the motors, and click 
run. Once you click run, the debugger stream will output
two values: the current sensor value and the time. You can
save this as a .csv and open it in excell to see the power 
curve.

If you output 127, you will get a close to linear curve. This
is becaues you are giving the lift too much power. The lower the power
is, the bigger the curve will show. Tune the values in POWER[4] to get 
biggest curve while still making your lift go all the way up.

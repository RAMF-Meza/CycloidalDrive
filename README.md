CycloidalDrive
==============

This is a motor drive to reduce the speed and increase torque, just like the common gear drives, but with cycloid disk which allows for a bigger reduction in a smaller space while reducing the backlash provided by the gear's tooths.

# What I Learned

* Define the reduction ratio needed for a given application
* What are cycloidal drives and how they work
* Using new tools in SolidWorks such as the "equation driven curve" to create a line segment when you have the corresponding equation
* It is way too important to select easy to find components such as bearings, pins, etc. it is not enough just to select comercial ones, but they have to be common enough so you can find them in most of the stores and also to get better prices.

# What would I improve?

* Improve the tolerances for assembly using GD&T

# Steps:

* Find the motor you will use (based on speed, torque, power, dimensions, etc.)
* Calculate how much torque and speed you need to increase/reduce for your application and with that find the ratio for the drive
* Use the Cycloidal.py script and change the parameters for the ones that you need
----------------------------
Run Command:

	python Cycloidal.py

 * Copy the provided equations for X and Y in the "equation driven curve" tool in solidworks
 * In the parameters make the curve from 0 to PI, and then you will mirror it (This avoids holes and errors)
 * With the parameters you selected for the script, add the corresponding holes for the pins to move correctly and for the shaft and extrude
 * Use this cycloidal disk you just created as a reference to create all the other components for your actuator
   

# SpaceApps2021 #
Above are the CAD Files for SpaceApps2021, for the challenge Let it Go: Without a Bang!

## Final Product Visuals ##

Using a piston inner radius of 0.5mm, and an outer radius of 2cm, we can achieve an extremely high force multiplier of 1599x! By applying just a 10N force to that, we can get max ~16kN of force applied opposing the preload! Best of all, this force is easily alterable based on the current flowing through the coil!

Here is a screenshot of our final assembly
![Final](https://github.com/Suputra/SpaceApps2021/blob/main/Hydraulic%20Force%20Multiplier.PNG)


Here is a link to animation:
https://youtu.be/h0p00UvmebA

## Mechanism Description with section views ##

### State 1 ###
![State 1](https://github.com/Suputra/SpaceApps2021/blob/main/Stage1.png)

State 1 is the initial state of the system - The coil has current running through it generating a magnetic field that pushes the inner piston up (which itself is a strong permanent magnet), applying a force on the hydraulic fluid. This force is magnified onto the outer piston due to its larger area.

### State 2 ###
![State 2](https://github.com/Suputra/SpaceApps2021/blob/main/Stage%202.png)

State 2 happens right after coil current switched - Current to coil is turned off, magnetic field collapses and reverses for a very short time- allowing the inner piston to fly back. Then, magnetic field is switched again when piston passes midpoint, and inner piston is further pushed back, resulting in lower pressure in the hydraulic valve/chamber and release of the outer piston.

### State 3 ###
![State 3](https://github.com/Suputra/SpaceApps2021/blob/main/Stage%203.png)

State 3 occurs after coil current switched back - as the pins retract, a torsion spring tensioning the latches is free to open the latch and release the device.

## Some Math ##
### Equation for Force Multiplication ###
![Force Multiplication](https://github.com/Suputra/SpaceApps2021/blob/main/force%20multiplication.png)

### Equation for Coil Magnetic Force ###
![Magnetic Force of a Solenoid](https://github.com/Suputra/SpaceApps2021/blob/main/Mag%20Force.png)

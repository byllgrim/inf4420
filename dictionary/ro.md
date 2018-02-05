ring oscillator (ro)
====================
an odd number of inverters connected in a ring.

mechanism
---------
one of the inverters input is set to 0 or 1, its output will then invert
this value, and the following inverter will invert that and so on.

since there's an odd number of inverters, the resulting input to our first
inverter will be opposite of what it started as.

this will continue forever, toggling between 0 and 1.

the speed/frequency is determined by the inverter propagation delay.
TODO and what else?

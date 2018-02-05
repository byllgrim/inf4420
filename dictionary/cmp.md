comparator
==========
compares if one signal is greater than another signal.

input offset
------------
switching point; 50% chance of output going hi or lo.
should _ideally_ be zero.

The probability is "resolved" by noise?

TODO rms input noise?

hysteresis
----------
comparator favors its current state.
'1' to '1' is more likely, as is '0' to '0'.

caused by internal capacitances.

opamp
-----
simple, but **slow** as a comparator.

mc creary: cancelling the offset voltage.
ϕ1 (reset): capacitor charget to zero (w/input offset).
ϕ2 (comparison): normal opamp comparator.

charge injection (clock feedthrough)
------------------------------------
charges injected into circuit when transistors turn off.
1. channel charge must flow out of terminals.
2. overlap capacitance between gate and junctions.

latched comparators
-------------------
preamp stage -> track-and-latch stage

preamp: higher resolution and minimize kickback.
track: amplify more.
latch: amplify more.

phase-locked loop (pll)
=======================
takes input signal, generates output with related phase.

simple design
-------------
1. vco (voltage controled oscillator) generates output
2. in and out is fed to phase comparator
3. a filter adjusts the comparator signal
4. ... and controls the vco

effect
------
generates a clock with same (or multiple) frequency as input.

used to
-------
* clock synchronization
* demodulation (TODO how?)
* frequency synthesis (TODO what?)
* recover signal from noise
* distribute clock

used in
-------
* radio
* telecom
* computers
* microprocessors

TODO
----
calculation problems.
exam relevant info.

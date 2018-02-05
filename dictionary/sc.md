switched capacitor (sc)
=======================
charge is moved in to the capacitor, then out the other side.

simple design (switched-capacitor resistor)
-------------------------------------------
a capacitor C has one terminal connected to two switches S1 S2.

when S1 closes (S2 open), charge qIN moves onto the capacitor.
when S2 closes (S1 open), charge qOUT moves out from the capacitor.

the switches alternate at a given frequency f.

charge formulas
---------------
    q = C V
    qIN = C VIN
    qOUT = C VOUT
    q = QIN - QOUT = charge moved out of capacitor
    q = C (VIN - VOUT)

resistance formulas
-------------------
    I = q f = continuous transfer of charge
    I = C (VIN - VOUT) f
    V = VIN - VOUT
    R = V / I = 1 / (C f)

usage
-----
* resistors in IC
* programmable (frequency) resistance
* track and hold (for e.g. adc)
* paracitic-sensitive integrator (fine tune opamp gain)

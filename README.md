# JetECU
Jet engine control software, plus tuning software!

**Welcome!**
JetECU is a MicroPython program designed to run on the Raspberry Pi Pico microcontroller. JetECU reads an input throttle, and opens and closes two solenoid gas valves depending on where that throttle percentage correlates to the timing map that is tuned via the JetECU tuning software.

Features I would like to add in the future:
  - Failsafe/Error correction
  - Self tuning (Like what Haltech/Nistune does for car ECUs)
  - Read input pressures of propellent/oxidiser
  - Some sort of "running" detection (Maybe with some sort of heat detection or knock sensor?)
  - In-depth error reporting

## Century clock
# This is a final project for my Digital Electronics class
# This project is about designing a circuit for a century clock: a normal clock which has the counters of seconds, minutes, hours, days, months and years. The years counter only counts from 1 to 99 then resets.
# No programmable kit like FPGA or similar is allowed for this project, only logic IC.
# The clock can be divided into 6 block, each for the time unit above. The seconds block uses the 1-second pulse generates from an Astable multivibrator circuit using IC NE555. Each timing block will have a circuit design consisting of logic ICs used to generate pulses to the next block, as well as to reset the value to its initial state. Moreover, every timing block (except the seconds block) will have a button to adjust the desire value.
# My group designed and simulated the clock on Proteus, before drawing the PCB on Altium and make it. 

## Deliverable 1 ##

![Alt text](deliverable1.png?raw=true "Deliverable 1")

## Deliverable 6 ##

This decoder chooses one of the 32 available registers based on a given address.  It does so with the following inputs: an enable bit, which indicates whether any of the registers should be written to, and a 5-bit address, which represents which register to write to if enable is high.  The enable bit is left shifted by the value of the address, a binary number between 0 and 31, to output the corresponding register index in the form of a 32-bit binary number with one "1" and 31 "0"s.
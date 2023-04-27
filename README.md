We want to design a sequential synchronous circuit with two binary inputs, x and x, and two binary outputs, y and y. The circuit should have the following specifications:

A. If the input values of x and x are 01, and then the circuit waits for 5 clocks (overlapping is allowed), and the values become 00 in two consecutive clocks, the output should be 11yy. This indicates a test for peace or not going to war in the battlefield.

B. If the values of x and x are 01 in two consecutive clocks, the output should be 01yy. The circuit should then wait for 5 clocks, and if the values of x and x remain the same, the output should be 10yy, indicating readiness for war without using conventional weapons.

C. If the values of x and x are 10 in two consecutive clocks, the output should be 01yy. The circuit should then wait for 5 clocks, and if the values of x and x remain the same, the output should be 10yy, indicating the start of a war with conventional weapons.

D. If the values of x and x are 11 in two consecutive clocks, the output should be 00yy, indicating a war with special weapons.

The clock frequency is 1Hz.

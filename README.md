# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: an integer overflow in a counter. The `buggy_counter.vhdl` file contains a VHDL implementation of a counter that counts from 0 to 15. However, if the counter attempts to exceed 15, it will result in an overflow, leading to unexpected behavior.

The `fixed_counter.vhdl` file provides a corrected version of the counter that addresses the overflow issue by using a modulo operator.
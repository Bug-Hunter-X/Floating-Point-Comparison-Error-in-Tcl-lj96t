# Floating-Point Comparison Error in Tcl

This repository demonstrates a subtle but common error in Tcl when comparing floating-point numbers for equality using the `==` operator.  Due to the inherent imprecision of floating-point representation, direct equality checks can lead to unexpected results.

The `bug.tcl` file shows the erroneous code, while `bugSolution.tcl` provides the corrected version. 

**Key takeaway:** Avoid direct equality comparisons for floating-point numbers. Use an epsilon-based comparison instead to check for near-equality.
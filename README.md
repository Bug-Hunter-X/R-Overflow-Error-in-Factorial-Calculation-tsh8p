# R Overflow Error in Factorial Calculation

This repository demonstrates a common error in R programming related to numerical overflow.  The `bug.R` file contains code that attempts to calculate the factorial of a very large number (1000). This calculation results in an extremely large number that exceeds R's numerical limits, leading to potential issues.

The `bugSolution.R` file provides a solution that addresses the overflow problem, ensuring accurate calculations for large factorials using the `gmp` package.
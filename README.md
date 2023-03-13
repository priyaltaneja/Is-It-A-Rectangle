# Is-It-A-Rectangle
## The Problem
Given four integers (A,B,C,D), determine whether or not they form a rectangle. Classically, we would need to consider all possible orderings of the four integers and check if any two adjacent pairs sum up to a value that is greater than or equal to the other two integers. Larger inputs could lead to a time-consuming computation.

## The Solution
On the other hand, quantum circuits can prepare a superposition of all possible orderings of the four integers in a single quantum state and perform the necessary checks in parallel. This means that it usually only takes one computation to determine whether or not the sidelengths are able to create a rectangle.

*This project was created as an application to the [QOSF mentorship program](https://qosf.org/qc_mentorship/).*

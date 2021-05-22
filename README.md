# Test-Quadratic-Equation
This exercise is about getting familiar with parametrized unit testing and JUnit 4.12 approach in particular.

First, you need to design and code a  method in the QuadraticEquation class.
Here are some details:

the method must solve a quadratic equation specified by three coefficients given as parameters: a,b,c.
first parameter  might not be zero. If it is, throw an IllegalArgumentException.
the  method return a string in of three formats:
x1 x2
x1
no roots
Next, you need to complete the test classes:

QuadraticEquationNoRootsCasesTesting
QuadraticEquationSingleRootCasesTesting
QuadraticEquationTwoRootsCasesTesting
QuadraticEquationZeroACasesTesting
Those are parameterized test classes, so take that into account. You have to provide at least 4 test cases for each one of the classes.
Also, you may not change signature of their constructors.

In order to pass the exercise, your tests must correctly detect flaws of some other sorting method implementations.
There are special tests in several classes that applies your tests to your and some of such bad implementations.

Your solution method must pass your tests, and others must fail in some cases.

This exercise is about getting familiar with parametrized unit testing and JUnit 4.12 approach in particular.
Design and code a solve method in the QuadraticEquation class.
Here are some details:

The method must solve a quadratic equation specified by the three coefficients given as parameters: a,b,c.
The first parameter can’t be zero. If it is the case, throw an IllegalArgumentException.
The solve method return a string in one out of three formats:


x1 x2 (two roots in any order separated by space) if there are two roots,

x1 (just the value of the root) if there is the only root,

no roots (just a string value "no roots") if there is no root.



Complete the test classes:

QuadraticEquationNoRootsCasesTesting
QuadraticEquationSingleRootCasesTesting
QuadraticEquationTwoRootsCasesTesting
QuadraticEquationZeroACasesTesting

Please consider that these are parameterized test classes.
You must provide at least 4 test cases for each class.
You are not allowed to change the signature of class constructors.
To pass the exercise, your tests must correctly detect flaws of some other sorting method implementations.
There are special tests in several classes that apply your tests to your implementation and other problematic (“bad”) ones.
Your solution method must pass your tests while other implementations must fail your tests in some cases.
There are special tests in several classes that applies your tests to your and some of such bad implementations:

DefaultQuadraticEquationTestingTest
ParamCarefulIncapableQuadraticEquationTestingTest
ParamCarefulTwoRootsReversedOrderQuadraticEquationTestingTest
ParamCarelessSingleRootOnlyQuadraticEquationTestingTest
ParamCarelessTwoRootsOnlyQuadraticEquationTestingTest

Hint: Quadratic formula reference

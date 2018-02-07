# Lecture 2. Linear Regression with One Variable
1. recap: 
	1. supervised learning: given the right answer for each example in the data;
	1. regression problem: real-valued output;
	1. classification problem:  discrete-valued output;

1. training set: example - housing price predict

1. training set -> learning algorithm -> hypothesis;
	1. h maps from x to y
	1. why + 1/2m? for math balabala? (1/2 is a convenience for the computation of the gradient descent)
	1. square error function = cost function (most commonly used one for regression problems)

1. contour plot

1. ##gradient descent## algorithm: 
	1. repeat updata theta 0 and theta 1 until convergence;
	1. use learning rate;
	1. need simultaneously update theta 0 and theta 1
	1. convex function: a bowl shape function
	1. batch gradient descent
	
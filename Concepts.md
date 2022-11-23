Given a set of data Y, X1, X2, X3, ... Xn

X: input/variable/independent variable/feature

Y: output/response

predition

inference

reducible error

irreducible error

parametric

non-parametric

feasible

non-feasible

Just like the name independent variable says, X is a variable that didn't depend on anythings.

Y however, is variable changing when ever X change. The input X can not have two Y as output.

Every data set can be written as Y = f(X) + ϵ. In this formulation, F is the information that X tells 
about Y and ϵ is the random error term, which is the error of the formula.
Using the formula Y = f(x) for a given data set, we can then predict Y when we can estimate f.
Sometimes we are not interested in making predictions and are more interested in the relation between Y and X, 
which is called inference.

A reducible error is an error that your model makes. You can minimize and even turning it to 0 by correcting the 
model.
Irreducible error is the random error term ϵ makes, which can't be minimized.

There are two ways of estimate Y, parametric and non-parametric.
Parametric is by using function f (X) = β0 + β1 X1 + β2 X2 + · · · + βp Xp to estimate f and then using another 
function Y ≈ f(x) to estimate Y.
The non-parametric method works out the function by fitting data in a function. So, for example, if there are two 
data points in the data set, work out a function that fits the data most, and when that data set has 3 data, 
another function that does, and so on.

Fleixble and non-flexible aproach is just another world of saying parametric and non-parametric.

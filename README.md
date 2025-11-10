# R-Syntax Workshop

## The Talking Points


## Part 1


### Operators and Values

R as a calculator has values and _operators_.

The _operators_ act on the values. 

The _relational_ operators compare the ordinality of the values: less than, greater than, equal, not equal.

The _logical_ operators act on a special kind of value: TRUE or FALSE

The mathematical operators act on numbers.


### Variables, Functions and Arguments

The values are stored in _variables_ using the assignment operator.

This facilitates working with values but naming variables is a hard problem.

Functions are like operators, they accept arguments to act on them.

The built-in functions have named and positional arguments.


## Part 2

### Data types and Data Structures

Introducing the most basic data structure, I give you the vector.

Did you know that vectors store values of the same data type in contiguous memory?

This makes them <span style="color:red">fast<span>.


### Your Humble Servant: The Mighty Vector

Vectors can be constructed with names.

There are short-cut syntax to build vectors using clever patterns.

Did I mention that R is vectorized by birth?

Physicist can split the atom but data scientists cannot split the R vector.



### More on Vectors

We call subsetting a vector, finding values that we are interested in.

We can subset by position or by a condition the values must satisfy.

We call these conditions: _masks_ when they return **TRUE** or **FALSE**.

We can also use a mask as a filter to extract only the values we are looking for. 

Can you glue two vectors to build a bigger one?

The NA is not to be confused with the DNA. It is a data thing and you should know about its genesis.

Factors: the vectors that store categorical values.


## Part 3

### The Matrix 

A bi-dimensional vector with its own bag of goodies.

Element-wise operators on matrices: not to be confused with algebraic matrix operations. 

Subsetting and appending a matrix.

Applied recycling.


## Part 4

### The List 

The section Using lists of vectors shows how a list is used to put labels on the x and y-axis of a matrix. One can spend a while studying this example. It shows an algebraic multiplication operator.

The section Subsetting by name or position is worth studying slowly. It is part of why this is called the `$` syntax in R. 

It is not trivial to learn, but it pays off handsomely to differentiate the meaning of the `[]` and `[[ ]]` operators. And the equivalence of the `[[ ]]` and the `$` to subset lists

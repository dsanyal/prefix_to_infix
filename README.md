# Prefix notation to Infix notation

#### What is infix notation?
**Infix notation:** X + Y

Operators are written in-between their operands. This is the usual way we write expressions. An expression such as `A * ( B + C ) / D` is usually taken to mean something like: "First add B and C together, then multiply the result by A, then divide by D to give the final answer."

#### What is prefix notation?
**Prefix notation (also known as "Polish notation"):** + X Y

In this case, operators are written before their operands. The expression given above is equivalent to `/ * A + B C D`. 

**Why would you use prefix notation?** 
Although it is difficult to read for humans, prefix notation has the advantage that does not require any parenthesis to indicate the sequence of operations. 


In this notebook, only native Python libraries are used to convert prefix notation to infix notation. One can also pass in range of values inside an expression, for e.g.
 '+ 5 x' where x = range(2,10)

 In this case, the code evaluates the expression for each of the values of 'x' and returns the maximum value.

I had fun while coding this up as part of a Python challenge, hope you like it :)
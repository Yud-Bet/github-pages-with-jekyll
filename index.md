# Yud Bet

1.1 Algorithms
Informally, an algorithm is any well-defined computational procedure that takes
some value, or set of values, as input and produces some value, or set of values, as
output. An algorithm is thus a sequence of computational steps that transform the
input into the output.
We can also view an algorithm as a tool for solving a well-specified computational problem. The statement of the problem specifies in general terms the desired
input/output relationship. The algorithm describes a specific computational procedure for achieving that input/output relationship.
For example, we might need to sort a sequence of numbers into nondecreasing
order. This problem arises frequently in practice and provides fertile ground for
introducing many standard design techniques and analysis tools. Here is how we
formally define the sorting problem:
Input: A sequence of n numbers ha1; a2;:::;ani.
Output: A permutation (reordering) ha0
1; a0
2;:::;a0
ni of the input sequence such
that a0
1  a0
2    a0
n.
For example, given the input sequence h31; 41; 59; 26; 41; 58i, a sorting algorithm
returns as output the sequence h26; 31; 41; 41; 58; 59i. Such an input sequence is
called an instance of the sorting problem. In general, an instance of a problem
consists of the input (satisfying whatever constraints are imposed in the problem
statement) needed to compute a solution to the problem.

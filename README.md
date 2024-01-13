# Data-Structures

Why DSA?
=> Makes you a better Software Developer
=> Helps you in getting a job
=> Winning the sport of competitive coding
=> To solve real-world problems

Analysis of Algorithms
Algorithm analysis is an important part of computational complexity theory.
Analysis of algorithms is the determination of the amount of time and space resources required to execute it.

Why Analysis of the Algorithm is important?
=> To predict the behavior of an algorithm without implementing it on specific systems.
=> It is impossible to predict the exact behavior of an algorithm since there are too many influencing factors.
=> The analysis is thus only an approximation not perfect.

Types of Algorithm Analysis
1. Best Case
2. Worst Case
3. Average Case

Asymptotic Analysis

=> The idea is to measure the order of growth
=> Does not depend upon the machine, programming language, etc.,
=> No need to implement we can analyze the algorithm.

order of growth
A function f(n) is said to be growing faster than g(n) if 
lim        g(n)/f(n) = 0 
n-> ∞

or 

lim      f(n)/g(n)  = infinity
n-> ∞

here f(n) and g(n) represent time taken where n >= 0 and f(n),g(n) >= 0

example: - 
lim   g(n)/f(n)  = 0
n-> ∞
f(n) = n^2 + n + 6
g(n) = 2n + 5

Lim  2n+5/ n^2 + n+ 6
n-> ∞

= Lim    (2/n + 5/n^2)/(1 + 1/n + 6/n^2)
  n-> ∞

 = Lim   0+0/1+0+0
   n-> ∞

= 0

hence f(n) is growing faster than g(n)

Direct way to find the order of growth
1. Ignore the lowest-order terms
2. Ignore the leading term constants

f(n) = 2n^2 + n + 6 order of growth = n^2 (quadratic)
g(n) = 100n + 3 oder of growth = n (linear)

how do we compare terms?
Constant < loglog n < log n < n^1/3 < n^1/2 < n < n^2 < n^3 < n^4 < 2^n < n^n


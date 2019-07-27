# TCS-CodeVita8-2019-Solution
This repository contains the solution of A question from TCS CodeVita 2019.
PROBLEM STATEMENT:
ITERATE BASE
Given a number representation, we can identify the base that would result in a least value for the representation. Consider:
For the number representation 11, the least possible base is 2 and hence, least possible value is 3 in base 10.
For 17, the least possible base is 8,thus, least possible value is 15 in base 10.
For 1729, the least possible base is 10 and least possible value is 1729 in base 10.

Consider doing this base reduction iteratively till a fixed point is reached as shown in the following example: Let's start with 72.
The least possible value of 72 is in base 8 and is 58 (in base 10). Iterating the least possible value of 58 is in base 9 and is 53 (base 10)
In the next iteration, 53 (in base 6) becomes 33. Then, 33(base 4) gives 15. 15(base 6) gives 11. 11(base 2) gives 3.
Finally 3 remains 3 in base 4 and above.

Write a program to accept a number representation, perform the successive base reductions as above and print the resulting final number.

Constraints:
Maximum base=36
Symbols used for digits: Base 2: 0,1
Base 3: 0,1,2
...
Base 11: 0,1,2,3,4,5,6,7,8,9,A
...
Base 36: 0,1,2,3,4,5,6,7,,8,9,A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z.

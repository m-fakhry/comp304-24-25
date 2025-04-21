# Lecture 7

## Bottom-up parser

- difference between top-down and bottom-up parsers 

- reverse of a sequence of right most derivations 

## Shift-reduce 

- Each step either to shift a terminal to the stack or reduce body of a production rule with its head 

- Sometime we can not decide which operation to use (shift or reduce), so choose randomly and backtrack if needed

- We can get into a conflict (shit-reduce or reduce-reduce conflicts)

- We discussed the algorithm for shift-reduce parser to parse any string 
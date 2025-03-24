# Lecture 6

## Grammar

- how to left-factor the grammar (remove common prefixes)

## Parser

- Backtracking if there are more than one production rule to pursue 

- Lookahead to predict which rule to use 

- First and Follow sets 

	- First: all terminals that start with

	- Follow: all terminals that follow the non-terminal 

- Construct the predictive parser table to predict which rule to use when non-terminal sees a terminal or end of file 

- LL(1) grammar has production rules of disjoint sets ((First and First) or (First and Follow))

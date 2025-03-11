# Lecture 5

- emphasize the role of scanner and table driven scanner 

## Grammar

- What is Grammar
	- Example: CFG for a mathematical expression (+, -, *, /, () , id)

- Derivation of string to test whether the string is accepted 

- left-recursive: the production rule that describes the non-terminal derives into a sequences where the first non-terminal in the seuqence is the same non-terminal the production rule describes

- how to eliminate the left-recursive 


## Parser

- top-dwn parser: recursive descend algorithm 

```
	- start with a pointer to the first token 
	- start with the start state in the grammar 
	- try to find the first production rule that leads to a sequence where the first terminal in the derived sequence is the current token 
	- if found 
		- accept the current token and advance to the next token 
		- advance to the next terminal or non-terminal in the  derived sequence. 
		- repeat 
	- not found
		- error 
```

- Example: language of $ba^*$. The following grammar:

```
S -> bA 
A -> aA | e
```

- we should have two functions, one for S() and one for A(). 



<!-- ### Scanner Types
	- table-driven
	- directed-code (each state is a function in the code)
	- hand-crafted scanner (using buffer to reduce IO operations) -->

<!-- - mention directed-code and hand-coded scanner  -->

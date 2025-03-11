# Assignment 5

## Reading 

- Read Section 3.3 P 96-103 (Top-Down Parsing). From the supplementary book, read p 217-220: Sections 4.4 and 4.4.1

## Paper 

How to solve the issue of a grammar such as 

```
S -> aA | aB | c 
A -> ...
B -> ... 
```

When implementing recursive-descend parser, which rule(s) will be used by the parser when the parser sees the token `a`? Should it use `aA` or `aB`? 

## Lab 

Implement a parser to describe the language $ba^*$. 
    
- Generate the output file of the scanner `output.txt`. 
    - This can be done by running the scanner implementation you previously developed to generate the sequence of tokens for the input string `baaa`
    - If you have not finished the scanner implementation, you can generate the `output.txt` file manually (this is not recommended). 

- Implement recursive-descend parser as described in the lecture
    - i.e. we need to have a function for each non-terminal which follows all production rules of the non-terminal, using if statement.

- The program should print whether the input string is accepted. 
    

**Objective**:

- Implement recursive function

- Test whether left-recursive grammar can be used. 
    - Validate the parser implementation by using CFG that is left-recursive and see if the program works correctly 
    
- Parser is the component responsible to test whether the input string is accepted 

**Skills**:

- Read list of tokens from a text file. What would be the data structure for list of tokens. 

- Understand CFG and problems of left-recursive grammar. 


## Optional - Lab 

Can you think of a way to implement the parser in agnostic way, such that the parser implementation does not depend on the grammar? Similar idea to what we have done in the scanner implementation. 
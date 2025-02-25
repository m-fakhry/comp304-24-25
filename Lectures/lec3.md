# Lecture 3

### Scanner Items
	- Token, Pattern, Lexeme 
	- Scanner returns BOTH lexeme and POS (token) using patterns (Regular Expression)
	- Scanner does not check grammar, but instead converts stream of characters into stream of tokens 
	- The only case where scanner (lexical analyzer) gives error is when the scanner can not recognize a token 

### FA and RE 
	- Regular expression, closure, concat, alter, parentheses
	- Single RE for each token
	- NFA and FDA
	- RE to NFA by adding empty moves, connecting and/or/closure
	- RE to NFA (Thompson) to DFA to minimal DFA

### Implementation Idea
	- More than one keyword into one, error state or non-terminal state are both indicating errors
	- Loop until reach the error state 
		- Accept characters from the input stream
		- make one transition
	- check the previous state 
		- if final: print the token corresponding to the current final state and then start over 
		- if not final: error and stop

<!-- ### Scanner Types
	- table-driven
	- directed-code (each state is a function in the code)
	- hand-crafted scanner (using buffer to reduce IO operations) -->
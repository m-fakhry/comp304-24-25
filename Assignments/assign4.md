# Assignment 4

1. Read more about CFG, left/right derivation, ambiguous grammar, left/right recursion. Section 3.2.2 (Context-Free Grammars), 3.2.3 (More Complex Examples), 3.2.4 (Encoding Meaning into Structure).

2. **(Lab)** Continue working on the previous assignment to implement a scanner based on automaton defined in text files.
    
    - Objective: 
        - When change the automaton (text files) the implementation of the scanner does not change, i.e., the user of your scanner implementation does not need to look at the code when the user changes the automaton because the automaton is described in external configuration (text) files.
        - To validate the idea, the task is after you implement the scanner, you apply it on different automata and different languages. Your implementation is correct if you do not need to change the code for different languages. The only change that you need to make is in the configuration (text) files that define the automaton and the input. 

    - Skills:
        - Read/Write text files 
        - Learn data structure suitable for any automaton
        - Make the scanner implementation agnostic to the automaton


# Assignment 3

1. From the supplementary book read (p 111-114), (p 120-124) and (p 128-135)
    - 3.1.2 (Tokens, Patterns, and Lexemes), 3.1.3 (Attributes for Tokens), 3.1.4 (Lexical Errors) 
    - 3.3.3 (Regular Expressions), 3.3.4 (Regular Definitions), 3.3.5 (Extensions of Regular Expressions) 
    - 3.4 (Recognition of Tokens) 
    - Optional 3.6 (Finite Automata), 3.7 (From Regular Expressions to Automata)

2. **(Paper)** 
    - Exercise 3.3.4 in the supplementary book: *SQL is a case insensitive language in which a keyword can be written either in lowercase or in uppercase, or in any mixture of cases. Thus, the SQL keyword SELECT can also be written select, Select, or sElEcT, for instance. Show how to write a regular expression for such a keyword*.
    - Write a regular expression that defines Comments in C++, which is any string surrounded by /* and */, without an intervening */, unless it is inside double-quotes ("). After you write the RE, convert it to NFA and then to DFA. **The FA should reject any invalid string and should accept any valid string**.

3. **(Lab)** We will redo the last lab assignment, but with an implementation of a scanner as described in the lecture. In particular, you need to do the following: 
    - Create four (and may be more) text files: 
        - Write a description for an automaton in a text file, names `automaton.txt`. 
        
            Ex: A possible format of the file could be one line defines all states, another line defines the start state, another line defines the final state, and the last line defines the error state. 
            ```
            q0, q1, q2, q3, q5, q6, q7
            q0
            q3, q5
            q7
            ```

            In the above format there are 8 states defined in the first line where the start state is q0 (as defined in the second line), the final states are q3 and q5, and the error states is q7. Note that this is not the only format that can be used to define the automaton, there are so many other formats that can be used. Be innovative and try to come up with a better format.
            
        - Write a description for the transition table in a text file, named `transition.txt`.
        - Write a description for the tokens associated with each final state in a text file, named `tokens.txt`.
        - Write the list of reserved words in a text file, named `keywords.txt`.
    - Write a C++ function that reads each of these text files and loads its information in an appropriate data structure. For example, the file `tokens.txt` could be loaded in an array of Struct, where the Struct has two members, `name` of the final state, and `value` that has the corresponding token. Again, you can come up with your own data structure, it is totally up to you to choose which data structure best fits which file. 
    - Write the implementation of the scanner as described in the lecture (see lecture notes).
    - Apply your program for a DFA for the **Graph coloring language** defined in the first assignment. 
# Lecture 2

## Scanner

- Definition of scanner: stream of characters to a stream of tokens
- Scanner (Lexical Analysis) Versus Parsing
- Recognition of Tokens ... recognize each word ... word by word
- Aggregation of characters to form a word, then determine whether or not it is a valid word, if valid, it assigns it a tag (part of speech) 
  - Example:
    convert the stream of characters
    <section>
      <pre><code data-trim data-noescape>
        int x;
      </code></pre>
    </section>
    to
    <section>
      <pre><code data-trim data-noescape>
        < data_type >
        < variable, i >
        < semicolon >
      </code></pre>
    </section>
- Transition Diagram / Table 
- Finite Automata
  - deterministic (DFA) and non-deterministic (NFA)
- How to handle a keyword when dealing with identifier
- Build FA for more than one keyword. 
- Algorithm for the scanner 

<!-- - Picture for the lecture
![Whiteboard](Images/lec2_1.jpg) -->

<!-- - **Exercise**

- Input Buffering
- Regular Expressions
  - Exercise: Exercise 3.3.2 : Describe the languages denoted by the following regular expressions
- Recognition of Tokens
  - Transition Diagram
- Finite Automata
  - DFA and NFA
  - NFA to DFA
  - Regular Expression to NFA
  - Regular Expression directly to DFA
 -->
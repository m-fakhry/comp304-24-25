# Compiler Desgin (COMP 304) - 2024-2025

- Repository for the Compiler Design undergraduate course (COMP 304) for the 2024-2025 academic year at Ain Shams University

### Logistics

Course | Compiler Design - COMP 304
---|----
Webpage| https://github.com/m-fakhry/comp304-24-25
Structure | 2-hour lecture (Monday 12-2pm) and 2-hour lab (Wed 2-4pm)
TAs | Kamel, Mohamed Essam, and Mohamed Mustafa (Alphabetical order)
Grades | 90 (final), 23 (midterm and exam), 37 (lab)
Lab Policy| Assignments, quizzes, and bonuses
Book | "_Engineering a Compiler_", Second Edition, Keith D. Cooper, Linda Torczon, 2012
Supplementary Book|"_Compilers - Principles, Techniques, and Tools_", Second Edition, Alfred Aho, Monica Lam, Ravi Sethi, Jeffrey Ullman, 2014 
Objective | Design and implement compilers
Skills | Programming languages, data structure, machine architecture, language theory, algorithms, and software engineering.
Tool |  [ANTLR](https://www.antlr.org/), [this link for computing First and Follow sets](https://www.usna.edu/Users/cs/wcbrown/courses/Su20SI413/firstFollowPredict/ffp.html), [SLR parser](https://jsmachines.sourceforge.net/machines/slr.html), [LR parsers](https://light0x00.github.io/parser-generator/)

---

### Lectures

Serial| Date |Topic | Contents | Lecture | Assignment
---|---|---|---|---|---
1| 2/10 | Introduction |Compiler vs Interpreter, Compiler Structure: scanner, parser, intermediate representation, optimizer, back-end  | [Lecture 1](Lectures/lec1.md) | [Assignment 1](Assignments/assign1.md)
2| 2/17|Scanner|Finite Automaton (DFA and NFA), How to build a scanner|[Lecture 2](Lectures/lec2.md) | [Assignment 2](Assignments/assign2.md)
3| 2/24|Scanner|RE, RE to NFA to DFA, Implementation of Scanner|[Lecture 3](Lectures/lec3.md) | [Assignment 3](Assignments/assign3.md)
4|3/3|Open Discussion|Lecture vs Assignment|[Lecture 4](Lectures/lec4.md) | [Assignment 4](Assignments/assign4.md)
5|3/10|Top-down Parser|CFG, Left-recursive, top-down parser, recursive descend|[Lecture 5](Lectures/lec5.md) | [Assignment 5](Assignments/assign5.md)
6| <s>3/17</s> 3/20|Top-down Parser|Backtracking, FIRST and FOLLOW sets, predictive parsing table, LL(1) grammar |[Lecture 6](Lectures/lec6.md)|[Assignment 6](Assignments/assign6.md)
7|3/24|Midterm exam|||
&#65279;|3/31|Day off|||
8| 4/7|Review Midterm| Review midterm exam||
9| 4/14|Bottom-up Parser| Reduction, right-most derivation, shift-reduce parser, conflicts|[Lecture 7](Lectures/lec7.md) | [Assignment 7](Assignments/assign7.md)
&#65279;| 4/21|Day off|||
10| 4/28|Bottom-up parser| Canonical item set, automaton, parsing tables, LR(0) and LR(1)|[Lecture 8](Lectures/lec8.md) | [Assignment 8](Assignments/assign8.md)
5/12|Lab Final|||[Notes](Assignments/notes.md)

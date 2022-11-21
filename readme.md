# Learning Path

```mermaid
  graph TD;
    1[6.00 Introduction To Computer Science And Programming]
    2[6.0001 Introduction To Computer Science And Programming In Python] --> 3[6.0002 Introduction To Computational Thinking And Data Science]
    4[6.001 Structure And Interpretation Of Computer Programs]--> 5[6.004 Computation Structures]
    6[6.005 Elements Of Software Construction]
    2 --> 7[6.006 Introduction To Algorithms]:::visited
    8[6.42J Mathematics For Computer Science] --> 7
    9[6.00SC Introduction To Computer Science And Programming]
    5 --> 10[6.033 Computer System Engineering]
    6 --> 10
    4 --> 11[6.034 Artificial Intelligence]
    13[6.170 Laboratory In Software Engineering] --> 12[6.035 Computer Language Engineering]
    14[6.036 Introduction To Machine Learning]
    16[18.01 Single Variable Calculus] --> 8
    8 --> 17[6.045J Automata, Computability, And Complexity]
    8 --> 18[6.046J Design And Analysis Of Algorithms]
    7 --> 18

    classDef visited fill:#f96;
```
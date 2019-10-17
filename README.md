# Theory-Of-Computations-Project

Problem Statement :- Program to construct a DFA which accept the language L = {anbm | n mod 2=0, m≥1}


In a DFA, for a particular input character, the machine goes to one state only. A transition function is defined on every state for 
every input symbol. Also in DFA null move is not allowed, i.e., DFA cannot change state without any input character.

DFA consists of 5 tuples {Q, ∑, q, F, δ}.
     Q : set of all states.
     ∑ : set of input symbols. 
     q : Initial state.
     F : set of final state.
     δ : Transition Function, defined as δ : Q X ∑ --> Q.
     

There are 3 steps involve which results in acceptance of string:

1. Construct FA for  means having even number of a’s.

2. Construct FA for  means having any number of b’s greater than one.

3. Concatenate the two FA and make single DFA.


Input: a a b b b 
Output: ACCEPTED // n = 2 (even) m=3 (>=1)

Input: a a a a 
Output: NOT ACCEPTED // n = 4, m = 0( must be >=1)


- THANK YOU.

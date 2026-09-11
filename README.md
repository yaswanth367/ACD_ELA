# NFA to DFA Conversion Using Subset Construction

## Overview

This project demonstrates the conversion of a Non-Deterministic Finite Automaton (NFA) into an equivalent Deterministic Finite Automaton (DFA) using the Subset Construction Method.

The main purpose of the project is to understand how an NFA, which can have multiple possible transitions for the same input, can be converted into a DFA where each state has a single transition for every input symbol.

## Objective

The objective of this project is to implement the NFA to DFA conversion process and visually represent the automata. The project helps in understanding the concepts of finite automata, state transitions, and subset construction.

## NFA

The project starts with an NFA containing three states, a binary input alphabet, one initial state, and one final state.

The NFA allows multiple possible states for certain inputs. This represents the non-deterministic behavior of the automaton.

## Subset Construction

The Subset Construction Method converts the NFA into a DFA by treating a group of NFA states as a single DFA state.

Starting from the NFA's initial state, the algorithm finds all possible states reachable for each input symbol. These sets of states become the states of the DFA. The process continues until all reachable combinations of NFA states have been identified.

A DFA state is considered a final state if it contains at least one final state of the original NFA.

## DFA

After applying subset construction, the resulting DFA represents the same language as the original NFA.

Unlike the NFA, the DFA has exactly one possible transition for each input symbol from every state. This makes the DFA deterministic.

## Visualization

Graphviz is used to visually represent the NFA and the resulting DFA. The diagrams make it easier to understand the states, transitions, initial state, and final states.

## Technologies Used

* Python
* Jupyter Notebook / Google Colab
* Graphviz
* IPython

## Applications

NFA to DFA conversion is an important concept in automata theory and is commonly used in compiler design, lexical analysis, pattern matching, regular expression processing, and formal language processing.

## Conclusion

This project provides a practical demonstration of NFA to DFA conversion using the Subset Construction Method. It shows how non-deterministic behavior can be represented using sets of states and transformed into an equivalent deterministic automaton.

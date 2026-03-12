# Trie Autocomplete and Spell Checker (C++)

This project implements a Trie data structure to support
efficient autocomplete and spell checking functionality.

The system loads a dictionary of words with frequency values
and provides suggestions based on prefix matching and
edit distance.

## Features
• Trie data structure implementation
• Prefix-based autocomplete
• Spell checking using edit distance
• Suggestions ranked by word frequency
• Fast search using Trie traversal
• Dictionary-based word lookup

## Technologies
C++
STL (unordered_map, vector, memory)
Data Structures (Trie)
Dynamic Programming (Edit Distance)

## How to Run

Compile the program:

g++ main.cpp trie.cpp editdistance.cpp -o trie

Run the program:

./trie

## Example Functions

1. Autocomplete
Input: "pro"
Output: program, process, product

2. Spell Checker
Input: "progarm"
Output: program

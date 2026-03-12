# Trie Autocomplete and Spell Checker (C++)

This project implements a **Trie (Prefix Tree) data structure** to provide fast autocomplete suggestions and basic spell checking functionality.

The system loads a dictionary of words with frequency values and returns suggestions based on prefix matching.  
Spell correction suggestions are generated using edit distance.

--------------------------------------------------

FEATURES

- Trie data structure implementation
- Fast prefix-based autocomplete
- Dictionary-based word lookup
- Spell check suggestions
- Suggestions ranked using word frequency
- Efficient search operations

--------------------------------------------------

TECHNOLOGIES USED

Language
- C++

Concepts
- Data Structures (Trie)
- Prefix Search
- Edit Distance for spell checking

Libraries
- C++ STL (vector, string, unordered_map)

--------------------------------------------------

PROJECT STRUCTURE

trie-autocomplete-spellchecker
|
|-- main.cpp
|-- trie.cpp
|-- trie.h
|-- editdistance.cpp
|-- sample_dictionary.txt
|
|-- README.md

--------------------------------------------------

HOW IT WORKS

1. Words are loaded from a dictionary file.
2. Each word is inserted into the Trie structure.
3. When a prefix is entered, the Trie is traversed to find matching words.
4. The system returns the top suggestions based on frequency.

--------------------------------------------------

COMPILATION

Compile the program using:

g++ main.cpp trie.cpp editdistance.cpp -o trie

Run the program:

./trie

--------------------------------------------------

TEAM PROJECT

This project was developed as a collaborative academic project.

My contributions included:
- Implementing the Trie data structure
- Developing prefix-based autocomplete functionality
- Integrating dictionary lookup and suggestion logic

The edit distance algorithm used for spell checking was implemented by my teammate.

--------------------------------------------------

FUTURE IMPROVEMENTS

- Larger dictionary dataset
- GUI-based interface
- Improved ranking of suggestions
- Performance optimization for large datasets

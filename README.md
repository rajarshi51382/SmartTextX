# SmartTextX

SmartTextX, also known as Project MOOCTextEditor, is a powerful text editing program developed as part of the Coursera course "Data Structure and Performance." This project aims to provide advanced features such as intelligent autocomplete, misspelled word flagging, and automatic spelling correction. The program consists of multiple modules, each focusing on different aspects of data structures and algorithms.

## Modules

### Module 1: Text Analysis and Complexity
Module 1 focuses on text analysis and complexity measurement. The assignment for this module involves generating the Text Complexity Score, a metric that quantifies the readability of a given text. The following files are introduced in this module:

- `document.DocumentX.java`: Provides the interface for working with documents.
- `document.BasicDocumentX.java`: Implements the basic functionality of a document.

### Module 2: Performance Optimization
Module 2 delves into performance optimization and benchmarking techniques. The main task in this module is to optimize the implementation of the `DocumentX` class from Module 1 and measure the resulting performance improvements. The file introduced in this module is:

- `document.EfficientDocumentX.java`: Implements an optimized version of the document.

### Module 3: Linked Structures and Testing
Module 3 focuses on implementing and testing linked data structures. The objective is to gain a deeper understanding of linked lists and their applications. The following files are introduced in this module:

- `textgen.MyLinkedListX*.java`: Implements a linked list data structure.
- `textgen.MarkovTextGeneratorX.java`: Provides a text generator based on the Markov chain algorithm.
- `textgen.MarkovTextGeneratorX*.java`: Additional helper classes for the Markov text generator.

### Module 4: Trees - Search and Suggestion
Module 4 explores various tree structures, including binary search trees and tries. The programming assignment in this module involves adding functionalities to flag misspelled words and provide automatic suggestions for the user's text as they type. The following files are introduced in this module:

- `spelling.SpellingSuggestX.java`: Provides suggestions for misspelled words.
- `spelling.AutoCompleteX.java`: Implements autocomplete functionality.
- `spelling.DictionaryX.java`: Represents a dictionary for word lookups.
- `spelling.DictionaryX*.java`: Additional classes for the dictionary implementation.
- `spelling.AutoCompleteDictionaryTrieX.java`: Implements autocomplete using a trie data structure.
- `spelling.TrieNodeX.java`: Represents a node in the trie data structure.

### Module 5: Hashing and Edit Distance
Module 5 covers hashing techniques and edit distance calculations. The programming assignment for this module involves implementing a highly practical feature that offers suggestions for correcting misspelled words. The following files are introduced in this module:

- `spelling.WordPathX.java`: Represents the path between two words.
- `spelling.NearbyWordsX.java`: Provides nearby word suggestions based on edit distance.
- `spelling.WPTreeX.java`: Implements a word prediction tree using hashing techniques.

## Usage
The SmartTextX program provides a robust backend for advanced text editing operations. Each module offers specific classes and methods that can be seamlessly integrated into other applications or used independently. The provided JavaFX-based frontend application, along with graders and tester classes, can be obtained separately from the University of California, San Diego (UCSD) to test and showcase the various module implementations.

For comprehensive instructions on how to utilize the features and functionalities provided by each module, please refer to the corresponding source code files and accompanying course materials.

## Contributors
SmartTextX, also known as Project MOOCTextEditor, was developed as part of the Coursera course "Data Structure and Performance." The initial code structure and course materials were provided by the University of California, San Diego (UCSD). The students enrolled in the course were responsible for implementing the required features and optimizing the code as part of their coursework.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to modify and distribute the code in accordance with the terms and conditions of this license.

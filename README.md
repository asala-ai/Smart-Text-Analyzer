# Smart Text Analyzer

### Data Structures Course Project

---

##  Overview

The **Smart Text Analyzer** is an interactive text-processing system developed as part of the Data Structures course.

The project demonstrates how fundamental data structures can be used to implement analytical and intelligent text features without relying on external NLP libraries.

The focus of this project is on efficient data organization, algorithmic reasoning, and structural design decisions.

---

##  Data Structures Applied

This system applies core data structures in practical scenarios:

* **List** → Sequential word and sentence storage
* **Dictionary (HashMap)** → Word frequency counting and N-gram modeling (O(1) average lookup)
* **Set** → Fast membership checking for vocabulary, stop words, and sentiment lexicons
* **Stack (List-based)** → Undo functionality using LIFO principle
* **Trie (Prefix Tree)** → Efficient prefix-based autocomplete
* **Nested Dictionaries** → Bigram and Trigram contextual prediction
* **Dynamic Programming** → Edit Distance algorithm for spell correction

Each structure was selected based on time complexity considerations and scalability.

---

##  Implemented Features

### 🔹 Analytical Features

* Word statistics (total words, unique words, top frequencies)
* Character statistics
* Word search with sentence reporting
* Word replacement with undo

### 🔹 Intelligent Features

* Smart Autocomplete (Trie-based)
* Bigram next-word prediction
* Trigram context prediction
* Spell check using Levenshtein Edit Distance
* Sentiment analysis with basic negation handling
* Keyword extraction using stop-word filtering
* Word cloud data preparation (normalized frequencies)

---

##  Algorithmic Focus

* Efficient frequency counting using hash maps
* Context modeling using N-grams
* Prefix search optimization using Trie
* Dynamic programming for edit distance computation

This project reflects the practical importance of data structures in building intelligent systems.

---

##  How to Run

```bash
python your_script_name.py
```

After running the program:

1. Choose to load text from a file or enter it directly.
2. Interact with the menu to explore the available features.

Make sure Python 3 is installed.

---

##  Developed By

Asala Abu Gharara
Sara Abu Mandeel

Data Structures Course
University College of Applied Sciences

---

> This project demonstrates the integration of core data structures with algorithmic thinking to simulate intelligent text-processing behavior.
ication of core data structures in building intelligent text-processing systems.

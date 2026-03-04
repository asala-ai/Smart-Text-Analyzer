# Smart Text Analyzer

### Data Structures Course Project

---

## 📌 Project Overview

The **Smart Text Analyzer** is an interactive text processing system developed as part of the Data Structures course.

This project demonstrates how fundamental data structures can be applied to build intelligent text analysis features similar to those used in real-world Natural Language Processing (NLP) systems.

Rather than relying on external NLP libraries, all core logic was implemented manually to emphasize understanding of:

* Efficient data storage
* Algorithmic optimization
* Time complexity considerations
* Structural design decisions

The system processes text and provides analytical and predictive features through a structured menu-driven interface.

---

## 🧠 Core Learning Objectives

This project focuses on applying Data Structures in practical scenarios, including:

* Efficient frequency counting using Hash Maps
* Fast membership testing using Sets
* Implementing Undo functionality using Stack (LIFO principle)
* Building a Trie (Prefix Tree) for autocomplete
* Constructing Bigram and Trigram models using nested dictionaries
* Implementing Edit Distance using Dynamic Programming

The goal was not only to build features, but to justify every structural choice based on efficiency and scalability.

---

## 🚀 Features

### 🔹 Text Processing

* Text preprocessing (lowercasing, punctuation removal, tokenization)
* Sentence extraction
* Word tokenization

### 🔹 Analytical Features

* Word Statistics (total words, unique words, top frequencies)
* Character Statistics
* Word Search with sentence position
* Word Replacement with Undo support

### 🔹 Intelligent Features

* **Smart Autocomplete** (Trie-based prefix search)
* **Bigram Next Word Prediction**
* **Trigram Context Prediction**
* **Spell Check** using Levenshtein Edit Distance
* **Sentiment Analysis** with basic negation handling
* **Keyword Extraction** using stop-word filtering
* **Word Cloud Data Preparation** using normalized frequencies

---

## 🏗 Data Structures Used and Justification

| Data Structure       | Usage                                     | Reason                        |
| -------------------- | ----------------------------------------- | ----------------------------- |
| List                 | Store words and sentences                 | Ordered sequential processing |
| Dictionary (HashMap) | Frequency counting, N-grams               | O(1) average lookup time      |
| Set                  | Vocabulary, stop words, sentiment lexicon | O(1) membership testing       |
| Stack (List-based)   | Undo functionality                        | LIFO behavior                 |
| Trie                 | Autocomplete                              | Efficient prefix-based search |
| Nested Dictionaries  | Bigram & Trigram models                   | Context-aware prediction      |

Using lists instead of dictionaries for frequency counting would require O(n) search per insertion, making the system inefficient for larger texts. Therefore, hash-based dictionaries were selected.

---

## 🔍 Algorithmic Components

### 1️⃣ N-gram Language Modeling

Bigram and trigram structures are built using nested dictionaries to simulate contextual word prediction.

### 2️⃣ Edit Distance (Dynamic Programming)

The Levenshtein algorithm is implemented manually to compute minimum edit operations for spell correction.

### 3️⃣ Prefix Tree (Trie)

Used to perform efficient autocomplete operations where search time depends on prefix length rather than total vocabulary size.

---

## 📂 Project Structure

```
Smart-Text-Analyzer/
│
├── main.py
├── sample_text.txt
├── README.md
└── report.pdf
```

---

## ▶️ How to Run

```bash
python main.py
```

Then choose to load text from file or direct input and interact with the menu.

---

## 🧪 Testing

The system was tested using structured sample text including:

* Repeated terms
* Predictable bigram/trigram sequences
* Positive and negative sentiment cases
* Invalid file paths
* Replacement and undo validation

All modules were verified to execute without runtime errors.

---

## 📈 Future Improvements

* GUI-based interface implementation
* Context-aware spell correction using probability
* Real-time text streaming using Queue
* Linked List-based dynamic editor simulation
* Export results to CSV or JSON

---

## 👩‍💻 Developed By

**Asala Abu Gharara**
**Sara Abu Mandeel**

Data Structures Course
University College of Applied Sciences

---

> This project reflects a practical application of core data structures in building intelligent text-processing systems.

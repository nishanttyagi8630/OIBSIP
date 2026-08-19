# Autocomplete & Autocorrect using NLP

## 📌 Project Overview

This project implements an NLP-based **Autocomplete and Autocorrect system** using the English text corpus from *Alice's Adventures in Wonderland*.

The project demonstrates how traditional Natural Language Processing techniques can be used for next-word prediction, character-based autocomplete, spelling correction, and performance evaluation.

The implementation combines **n-gram language modelling, word-frequency analysis, prefix matching, PySpellChecker, and Levenshtein edit distance**.

---

## 🎯 Objectives

The main objectives of this project are:

- Perform NLP preprocessing on a large text corpus.
- Build frequency-based n-gram models for autocomplete.
- Implement Bigram and Trigram based next-word prediction.
- Implement character-prefix autocomplete.
- Develop an autocorrect system for misspelled words.
- Compare PySpellChecker with a custom Levenshtein-distance approach.
- Evaluate models using accuracy, precision, and recall.
- Visualize word frequencies and autocorrect performance.
- Analyse the limitations of traditional NLP approaches compared with production systems.

---

## 📚 Dataset

### Alice's Adventures in Wonderland

The project uses the text of *Alice's Adventures in Wonderland* as the language corpus.

The text is loaded into Python and processed to create a clean vocabulary for autocomplete and autocorrect operations.

### Preprocessing

The following preprocessing steps were performed:

1. Converted text to lowercase.
2. Removed punctuation and non-alphabetic characters.
3. Tokenized the text into individual words.
4. Removed non-word tokens.
5. Created word-frequency statistics.
6. Generated bigram and trigram sequences.

---

## 🧠 NLP Techniques Used

### 1. Bigram Model

A Bigram model predicts the next word based on the previous word.

Example:

```text
Input: the
Prediction: rabbit, queen, ...

## Author
Nishant Tyagi — Data Analytics Intern, Oasis Infobyte

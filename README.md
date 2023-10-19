# Learning_NLP
I will use this repository to store what I have learned about Natural Language Processing from the Language Technology course.

# Lab0: Spell Checker
Basically, the goal of the spell checker program is to return a the word that is the most probable correction to $w$ by using a dictionary of known words along with the probability of each word to occur. To create this dictionary the program uses a text file $big.txt$ of about a million word (concatenation of public domain book excerpts).

for more information about the program:
https://norvig.com/spell-correct.html

# Lab1: Indexer
The goal of this lab is to create an index of all the words in a set of documents with the position of each word in the documents. We will call this a master index. Then, we will calculate the tf-idf values for each pair of document-word. Finally, we represent the similarity between each pair of documents.

# Lab2: Language Models
In this lab, we aim to calculate the probability of a sentence using Unigrams, Bigrams and Trigrams. Then we write a program that predicts the next word using the last two words in a sentence.

# Lab3: Byte-Pair Encoding
In this lab we discussed the sub-word tokenization using Byte-Pair Encoding and the Unigram
model techniques.

# Lab4: Language Detector
The purpose of this lab is classifying languages using neural networks with sklearn and PyTorch
libraries. The program is inspired by Google Compact Language Detector, version 3 (CLD3), a
neural network architecture for language identification.

# Lab5: Chunker
On this lab we trained different recurrent networks to predict the syntactic groups of each
word in a sentence.

# Lab6: Training the Transformer from "Attention Is All You Need"
In this lab we train the Transformer Architecture from the famous paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) that had a profound impact not just on natural language processing but all fields of machine learning and AI.

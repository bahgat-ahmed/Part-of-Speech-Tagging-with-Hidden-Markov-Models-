# Part-of-Speech-Tagging With Hidden Markov Model

![GitHub Logo](_post-hmm.png)

## Introduction

This is the project I have built in the first course of the **NLP Nanodegree**. The course name is **Introduction to Natural Language Processing**.

In this notebook, I've used the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

The notebook already contains some code to get me started. I have only needed to add some new functionality in the areas indicated to complete the project; I did not need to modify the included code beyond what is requested. Sections that begin with **'IMPLEMENTATION'** in the header indicate that I must provide code in the block that follows. Instructions was provided for me for each section, and the specifics of the implementation are marked in the code block with a `'TODO'` statement. 

## The Road Ahead

The section on Step 4 includes references & resources you can use to further explore HMM taggers.

* Step 1: Review the provided interface to load and access the text corpus
* Step 2: Build a Most Frequent Class tagger to use as a baseline
* Step 3: Build an HMM Part of Speech tagger and compare to the MFC baseline
* Step 4: (Optional) Improve the HMM tagger

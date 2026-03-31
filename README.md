# README: NLP Fundamentals Workshop - POS Tagging & Language Models

## Overview
This workshop provides a hands-on, interactive introduction to the foundational pillars of Natural Language Processing: **Part-of-Speech (POS) Tagging**, **Probabilistic Language Modeling**, and **Model Evaluation**. Designed for Data Science and AI students, this curriculum moves beyond static slides to a dynamic "Lab-First" environment using Jupyter Notebooks, NLTK, and AI-assisted visualization.

## Learning Objectives
By the end of this session, participants will be able to:
* [cite_start]**Categorize** words into Open and Closed classes and apply the Penn Treebank tagset.
* [cite_start]**Implement** various tagging architectures, from simple Regex to Classifier-based models.
* [cite_start]**Construct** N-gram models using the Chain Rule and Markov Assumption.
* [cite_start]**Solve** data sparsity issues ("The Problem of Zeros") using Laplace (Add-1) Smoothing.
* [cite_start]**Evaluate** models using Intrinsic (Perplexity) and Extrinsic (Downstream task) metrics.

---

## Project Structure
The workshop is divided into three distinct phases, each contained within its own Jupyter Notebook:

### 1. Phase 1: The Anatomy of Language
* [cite_start]**Theory:** Exploration of POS tagging as the process of assigning grammatical labels to tokens. 
* [cite_start]**Interactive Lab:** A "Human Tagger" competition where students manually tag sentences and compare their results against the **NLTK** automated tagger and the **Wall Street Journal (WSJ) Gold Standard** corpus.
* **Visual Twist:** Conceptualizing word classes through the "POS Anatomy Monster."

### 2. Phase 2: The Math of Prediction
* [cite_start]**Theory:** Understanding the **Chain Rule** and how the **Markov Assumption** simplifies complex histories into manageable N-grams.
* [cite_start]**Interactive Lab:** Building a Bigram probability engine using **Maximum Likelihood Estimation (MLE)** to predict the next word in a sequence.
* **Visual Twist:** A cinematic visualization of "look-back" context windows in predictive typing.

### 3. Phase 3: The Reality Check
* [cite_start]**Theory:** Addressing why MLE fails on unseen data (the "Zero" problem) and how **Smoothing** (Add-1) and **Interpolation** provide mathematical safety nets.
* [cite_start]**Interactive Lab:** Calculating **Perplexity** to measure model "surprise" and discussing the trade-offs between intrinsic math and extrinsic real-world performance.
* [cite_start]**Visual Twist:** The "NLP Kitchen" metaphor for Backoff and Interpolation strategies.

---

## Technical Requirements
To run these notebooks, ensure you have the following environment configured:
* **Python 3.10+**
* **Virtual Environment (.venv)**
* **Required Libraries:** ```bash
  pip install nltk ipykernel
  ```
* **NLTK Data:** The notebooks will automatically attempt to download `punkt_tab`, `averaged_perceptron_tagger_eng`, and `treebank`.

## Educational Philosophy
This workshop utilizes **Active Learning** and **Instructional Design** principles. By integrating AI-generated visual metaphors (via Veo and Gemini) and real-time data exploration in VS Code, we bridge the gap between abstract statistical theory and modern industrial application. The goal is to demystify the "black box" of language models, showing that even the most advanced LLMs are rooted in these fundamental probabilistic identities.
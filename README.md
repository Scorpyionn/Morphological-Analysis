# Experiment 5: Morphological Analysis and POS Tagging

## Overview
This experiment implements Morphological Analysis and Part-of-Speech (POS) Tagging using Python and the NLTK (Natural Language Toolkit) library.

The experiment uses a Wildlife Conservation dataset to analyze the grammatical structure and linguistic properties of words.

## Objectives
- Understand morphological analysis and word structure.
- Perform tokenization of text data.
- Apply stemming using Porter Stemmer.
- Perform lemmatization using WordNet Lemmatizer.
- Identify grammatical categories using POS tagging.
- Extract noun phrases using NP chunking.
- Calculate POS tag frequency distributions.
- Visualize results using bar charts.

## Technologies Used
- Python 3
- Google Colab
- NLTK
- Pandas
- Matplotlib

## Dataset
The experiment uses five sample sentences based on Wildlife Conservation and Forest Protection.

Example:
- Wildlife conservation protects endangered animals.
- Forest guardians are planting trees in damaged areas.
- Elephants migrate across large grasslands.
- Environmental scientists study animal behavior carefully.
- National parks provide safe habitats for rare species.

## Implementation Steps
1. Import the required Python libraries.
2. Download the necessary NLTK resources.
3. Create the text dataset.
4. Perform word tokenization.
5. Apply stemming using Porter Stemmer.
6. Apply lemmatization using WordNet.
7. Perform Part-of-Speech tagging.
8. Generate morphological analysis tables.
9. Extract noun phrases using chunking.
10. Calculate POS tag frequency.
11. Visualize POS tag distribution using a bar chart.
12. Generate the final analysis table.

## Installation

Install the required libraries:

```bash
pip install nltk pandas matplotlib
```

Download the required NLTK resources:

```python
import nltk

nltk.download('punkt_tab')
nltk.download('averaged_perceptron_tagger_eng')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('stopwords')
```

## Repository Structure

```text
NLP_Practical_Experiments/
│
├── Experiment_5_Morphological_Analysis.ipynb
│
└── README.md
```

## Expected Output
The experiment generates:

- Tokenized words
- Stemmed and lemmatized words
- POS tagging results
- Morphological analysis table

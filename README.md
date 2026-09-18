# Odyssey NLP Analysis

Independent computational text analysis of Homer's *The Odyssey*, comparing characters' language patterns and demeanor across the epic using classic NLP techniques.

## Goal

Analyze how different characters and books in *The Odyssey* are linguistically distinct, using word associations, embeddings, and vocabulary patterns to compare characters' demeanors and how their fates in the story connect to the language surrounding them.

## Methods

- **TF-IDF scoring**: measured word importance across books to compare characters (e.g., contrasting hospitable language associated with different hosts like Alcinous, Eumaeus, Nestor, and Menelaus)
- **Word embeddings**: trained a Word2Vec skip-gram model on the preprocessed text to find words most and least similar to key characters and concepts, and to explore analogies (e.g., host-to-guest relationships across different characters)
- **Vocabulary and distinctive word analysis**: identified the most common and most distinctive words per book and per character to highlight tonal and thematic differences across the epic

## Preprocessing

Preprocessed 12,000+ lines of text with lemmatization and stopword removal before running any analysis.

## What's here

- `odyssey_analysis.ipynb`: full analysis pipeline and results
- Full write-up available on [LinkedIn](https://www.linkedin.com/in/adrian-filip-/)

## Note

This was an early independent project, completed freshman year. Some code reflects earlier stylistic habits compared to more recent projects, but the analysis and results remain intact.

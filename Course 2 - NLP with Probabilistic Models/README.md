# NLP with Probabilistic Models - Course 2

## Course Description
  - Create an **Auto correct models** that calculates probabilities to find the most likely correction of a typo, through considering different possible edits to correct the typo and calculating the minimum edit distance to correct a certain word.
  - **Part of speech tagging (POS)** using **hidden Markov model** with the **Viterbi** algorithm. The Viterbi algorithm makes use of dynamic programming, which is an optimization technique that breaks down a big problem into smaller problems;
  - **Part 03**:
    - N-Grams and probabilities;
    - Approximate sentence probability from N-Grams;
    - Build a language model from a corpus;
    - Fix missing information;
    - Out of vocabulary words with <UNK>;
    - Missing N-Gram in corpus with smoothing, backoff and interpolation;
    - Evaluate language model with perplexity.

## Notebok Description
  - 1. **Building_Vocabulary_Model.ipynb**: Vocabulary Creation with a small corpus;
  - 2. **Numpy_Operations.ipynb**: Parts-of-Speech Tagging - Working with tags and Numpy. Creates a matrix using some tag information and then modify it using different approaches;
  - 3. **Candidates_from_Edits.ipynb**: Listing candidates from string edits by applying edit operations;
  - 4. **Autocorrect_MinEditDistance_Assignment.ipynb**: Implement an auto-correct system using minimum edit distance;
  - 5. **Strings_and_Tags.ipynb**: Working with text files, creating a vocabulary and handling unknown words;
  - 6. **Part_of_Speech_Tagging_POS.ipynb**: Building a Parts-of-Speech Tagging model. Goes through the process of assigning a part-of-speech tag (e.g. Noun, Verb, Adjective) to each word in an input text. Tagging can be difficult because some words can represent more than one part of speech at different times;
  - 7. **N-grams_Corpus_preprocessing.ipynb**: Applying common preprocessing steps for the language models and creating N-grams from sentences;
  - 8. **Building_the_language_model.ipynb**: Calculating n-gram probability by counting frequencies of n-grams and n-gram prefixes in a training dataset.



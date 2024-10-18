# One Model To Rule Them All? Multilingual NLP

### Overview

This project explores multilingual Natural Language Processing (NLP) by analyzing the morphological complexity of various languages using metrics such as Type-Token Ratio (TTR) and perplexity. The primary tools used in this project are **KenLM** for language modeling and **Polyglot** for tokenization.

### Key Concepts

1. **Type-Token Ratio (TTR)**:
   - TTR is defined as the ratio of unique tokens to the total number of tokens. It serves as a measure of linguistic diversity and morphological complexity.
   - High TTR indicates high lexical diversity, while low TTR suggests more repetitive language use.
   - Other metrics for quantifying morphological complexity include Morphological Complexity Index (MCI) and Mean Length of Utterance (MLU).

2. **Language Modeling**:
   - Language modeling involves predicting the next word or character in a document, enabling applications in text generation, classification, and question answering.
   - In this project, we utilize **KenLM**, a high-performance language model, to compute perplexity across different languages, facilitating the evaluation of model performance.

3. **Perplexity**:
   - Perplexity measures a language model’s uncertainty in predicting the next word. Lower perplexity indicates better predictive accuracy.
   - While comparing perplexity across languages can be challenging, it helps analyze the performance of models within morphological categories.

### Data Preparation

- The corpus used in this project is the **Wiki40B** dataset, which provides high-quality, structured data suitable for NLP tasks.
- We employ **Polyglot** for tokenization, leveraging its capabilities to segment sentences into tokens efficiently. Polyglot uses Unicode character properties and language-specific rules to identify sentence boundaries, ensuring accurate tokenization.

### Experimentation

1. **Dataset Extraction**:
   - Extract 40,000 unique sentences for each language for the training set and 3,000 for the test set.
   - Remove duplicate sentences to ensure accurate evaluation metrics.

2. **Tokenization**:
   - Use **Polyglot** to tokenize the datasets into words, saving each dataset in a consistent format for automated language model estimation.

3. **TTR Computation**:
   - Compute TTR for all datasets and store the results in a structured DataFrame for better analysis.

4. **Language Modeling with KenLM**:
   - Train a language model for each language using **KenLM** and compute perplexity scores to evaluate model performance.
   - Store the perplexity results in an organized structure for analysis.

5. **Visualizing Results**:
   - Plot the relationship between TTR and perplexity across languages to illustrate findings.

### Conclusion

The findings of this project indicate that languages with higher morphological complexity tend to exhibit higher TTR and perplexity scores. By using **KenLM** for language modeling and **Polyglot** for tokenization, this project provides valuable insights into the challenges faced by language models in handling diverse linguistic structures.

### Installation and Requirements

To run this project, please ensure the following libraries are installed:

```bash
pip install kenlm polyglot

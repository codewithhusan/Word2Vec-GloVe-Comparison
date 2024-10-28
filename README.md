# 🌟Comparative Analysis of Word Embedding Models on Shakespearean Texts

This project is an assignment for COMP 3704, analyzing word embedding models—CBOW, Skip-gram, and GloVe—trained on a Shakespearean text corpus. The analysis focuses on how each model captures meanings and relationships between terms in Shakespearean English.

## 📊Project Overview

The goal of this project is to compare the capabilities of various word embedding models on Shakespearean texts by analyzing their ability to capture semantic relationships. The models were evaluated by examining the similarities between specific terms and linear combinations of vectors, providing insights into each model's strengths and weaknesses.

### 💡Key Components

1. **Model Training**:
   - CBOW and Skip-gram models were trained on cleaned Shakespearean text data, using `gensim.models.Word2Vec`.
   - The pretrained GloVe model (`gensim.models.KeyedVectors`) was loaded for comparison.

2. **Word Vector Analysis**:
   - Found the most similar terms for individual words like *hamlet*, *nature*, *spirit*, etc., and observed how each model interprets these terms.
   - Evaluated term similarities for specific word pairs, e.g., (*brutus*, *murder*), (*macbeth*, *hamlet*).
   - Analyzed linear combinations of word vectors to understand how each model interprets combined meanings.

3. **Findings**:
   - Provided a detailed comparative analysis, highlighting each model's ability to capture word meanings and contextual relationships.
   - Suggested potential improvements for training word embeddings more tailored to Shakespearean English.

## 🔄File Overview

- **Comp_3704_Assignment_4.ipynb**: Jupyter notebook containing the code for training models, performing similarity analysis, and discussing results.

## 🛠Installation and Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/codewithhusan/Word2Vec-GloVe-Comparison.git
    cd Word2Vec-GloVe-Comparison
    ```

2. **Dependencies**:
   - Python 3.x
   - Jupyter Notebook
   - Gensim
   - Numpy
   - Pandas

   Install dependencies via pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Running the Notebook**:
   - Open the notebook in Jupyter:
     ```bash
     jupyter notebook Comp_3704_Assignment_4.ipynb
     ```
   - Run each cell sequentially to train the models, analyze results, and view conclusions.

## 🎯Results Summary

The analysis found that:
- **CBOW Model**: Performed best in general term similarity but was less context-specific.
- **Skip-gram Model**: Captured more nuanced relationships, though sometimes introduced unrelated terms.
- **GloVe Model**: Provided broad, statistically-coherent terms but occasionally missed context-specific details.

For further analysis and detailed results, please refer to the notebook.

## 🚀Future Improvements

To develop a better model for Shakespearean text, future work could include training with additional Elizabethan literature, incorporating annotated corpora, and fine-tuning with a broader set of thematic resources.

---

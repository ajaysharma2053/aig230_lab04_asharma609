# AIG 230 – Lab 04  
## Word Embeddings and Semantic Representations

### Overview

In this lab, I explored **word embeddings**, which are learned vector representations of words based on their surrounding context in text data.  
Unlike traditional count-based approaches such as bag-of-words or n-grams, word embeddings provide **dense and meaningful representations** that capture semantic relationships between words.

The lab focused on understanding how meaning can be learned from word co-occurrence patterns and how these representations are applied in practical natural language processing tasks.

---

### Learning Outcomes

By completing this lab, I was able to:

- Understand **distributional semantics** and how word meaning emerges from context  
- Train word embedding models using **Word2Vec** and **FastText**
- Measure semantic similarity using **cosine similarity**
- Interpret nearest neighbors in embedding space
- Perform **vector arithmetic (word analogies)** and understand why it works
- Visualize high-dimensional embeddings using dimensionality reduction
- Compare Word2Vec and FastText, especially for rare and unseen words
- Identify realistic industry use cases and limitations of word embeddings

---

### Concepts Covered

The main concepts covered in this lab include:

- Learned representations vs manually engineered features  
- The distributional hypothesis (“a word is known by the company it keeps”)  
- Word2Vec architectures (Skip-gram and CBOW at a conceptual level)  
- Semantic similarity and nearest-neighbor search  
- Vector-based analogies  
- Visualization of embedding spaces using PCA  
- FastText and subword information  
- Conceptual comparison with other embedding approaches such as GloVe  
- Practical challenges and evaluation considerations when using embeddings  

---

### Tools and Libraries Used

The following tools and libraries were used throughout the lab:

- **Gensim** for training Word2Vec and FastText models  
- **scikit-learn** for dataset loading and dimensionality reduction  
- **NLTK** for text preprocessing and tokenization  
- **matplotlib** for visualizing embedding spaces  

---

### Dataset

This lab uses the **20 Newsgroups** dataset, which contains text documents from multiple topic areas such as technology, science, politics, and religion.

The dataset represents real-world text data similar to what is commonly found in forums, customer support systems, and online discussion platforms.

---

### Work Completed

In the lab notebook, I completed the following tasks:

- Preprocessed and cleaned the text data  
- Trained Word2Vec models with different parameter settings  
- Compared the effects of **window size**, **vector dimensionality**, and **training methods (CBOW vs Skip-gram)**  
- Evaluated semantic similarity using nearest neighbors  
- Compared Word2Vec and FastText behavior for out-of-vocabulary words  
- Added **bigrams** to improve representations of multi-word concepts  
- Reflected on how different design choices affect embedding quality  

Each section includes checkpoint questions to support interpretation and understanding of the results.

---

### Files Included
 
  The completed lab notebook containing:
  - Code implementation  
  - Visualizations  
  - Experimental comparisons  
  - Written explanations and reflections  

---

### How to Run

1. Open the notebook in Jupyter Notebook or VS Code  
2. Run all cells from top to bottom  
3. Ensure all checkpoint questions are answered  
4. Confirm that the notebook runs without errors  

---

### Key Reflection

This lab demonstrates a shift from simply **counting words** to **learning semantic meaning** from data.  
Word embeddings form a foundational component of modern NLP systems and are widely used in applications such as semantic search, recommendation systems, and text classification.

Understanding how embeddings are trained, evaluated, and interpreted is essential for building reliable and responsible NLP solutions.

---

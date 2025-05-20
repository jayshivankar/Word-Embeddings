# Word2Vec with Gensim – Notebook Tutorial

This repository contains a Jupyter Notebook (`42_word2vec_gensim.ipynb`) that demonstrates how to train and use Word2Vec models using the [Gensim](https://radimrehurek.com/gensim/) library in Python.

## 📘 About

Word2Vec is a popular algorithm for learning word embeddings from raw text. This notebook covers:

- Preparing text data for Word2Vec
- Training a Word2Vec model using Gensim
- Exploring vector similarity
- Finding most similar words
- Visualizing word vectors (optional)
  
The notebook is beginner-friendly and suitable for NLP enthusiasts and data science students.

## 🧰 Requirements

To run this notebook, you’ll need the following Python libraries:

```bash
pip install gensim nltk matplotlib
```

## 🚀 Getting Started

1. Clone the repository or download the notebook file.
2. Install the dependencies.
3. Open the notebook with Jupyter:

```bash
jupyter notebook 42_word2vec_gensim.ipynb
```

## 📂 Notebook Sections

- **Text Preprocessing:** Cleaning and tokenizing raw text
- **Model Training:** Using `gensim.models.Word2Vec`
- **Similarity Checks:** Finding similar words, odd-one-out, etc.
- **Vector Operations:** Understanding how word relationships are encoded
- **(Optional)** Visualizations using PCA or t-SNE

## 🧪 Example Output

```python
model.wv.most_similar('king')
# Output: [('queen', 0.89), ('prince', 0.85), ...]
```

## 📚 References

- [Gensim Documentation](https://radimrehurek.com/gensim/models/word2vec.html)
- [Mikolov et al., 2013 - Word2Vec paper](https://arxiv.org/abs/1301.3781)



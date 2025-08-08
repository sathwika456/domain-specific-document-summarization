 🧠 Domain-Specific Document Summarization through Hierarchical Classification using Transformers

A Natural Language Processing (NLP) project that tackles the challenge of analyzing and summarizing scientific literature from PubMed using classification models and deep learning transformers like BART.



📌 Project Overview

- Goal: Automate classification and summarization of scientific text data
- Dataset: 50,000+ articles from PubMed with MeSH labels
- Techniques Used: Doc2Vec, PCA, Logistic Regression, SVM, Neural Networks, BART
- Team Size: 4



 🛠️ Features

- Doc2Vec for semantic document embeddings
- Dimensionality reduction with PCA for visualization
- Multi-label classification using:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Neural Networks (shallow + deep)
- Text summarization using the BART transformer model
- Data visualization: 3D clustering by Mesh labels
- Comparison of model performance via precision, recall, F1-score



 📂 Project Files

| File                                 | Description                                       |
|--------------------------------------|---------------------------------------------------|
| `NLP_project_final.docx`             | Final report detailing methodology and results   |
| `PubMed.csv`                         | Dataset of 50K+ scientific abstracts (not public) |
| `Final_Presentation.pptx`           | Presentation slides summarizing the project      |
| `TransformerProjectNotebook.ipynb`   | Python code with full model implementation       |



 📊 Tools & Libraries

- Python (pandas, gensim, sklearn, matplotlib, seaborn, nltk)
- Hugging Face Transformers (BART)
- MySQL (for structured storage)
- Jupyter Notebook
- Microsoft Word & PowerPoint (for reporting)



👥 Team Members

- Sathwika Karingu
- Vivek Nelluri
- Hemanth Addepalli
- Chilukuri Tagore Reddy



🧠 Summary

This project demonstrates a full NLP pipeline for domain-specific text classification and summarization, integrating classical ML models with modern deep learning (transformers). Its modular structure supports adaptation for biomedical, legal, and other structured corpora.



 📎 References

- Chidanand Shetty et al., ICCES 2021
- Liu et al., ACM Recommender Systems 2016
- [Cornell Movie Review Dataset](https://www.cs.cornell.edu/people/pabo/movie-review-data/)
- [Real-World ML Book](https://livebook.manning.com/book/real-world-machine-learning/)
- [arXiv Preprint](http://xxx.lanl.gov/abs/cs/0409058)
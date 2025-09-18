# Legal Document Summarization

## 📌 Project Overview
This project provides an approach to automatically summarize legal documents using Natural Language Processing (NLP) techniques.  
The main goal is to extract concise and meaningful summaries from lengthy legal texts while preserving important context.

## 📂 Repository Contents
- `Legal_Document_summarization.ipynb` → Jupyter Notebook containing code for preprocessing, summarization, and evaluation.

## ⚙️ Requirements
Make sure you have the following installed:

- Python 3.8+  
- Jupyter Notebook  
- Required Python libraries:
  ```bash
  pip install -r requirements.txt
(or manually install: numpy, pandas, nltk, transformers, scikit-learn, etc.)

🚀 How to Run
Clone this repository:

git clone https://github.com/your-username/legal-document-summarization.git
cd legal-document-summarization
Open the Jupyter Notebook:

jupyter notebook Legal_Document_summarization.ipynb
Run the cells step by step to preprocess data, generate summaries, and evaluate results.

📊 Features
Text preprocessing (tokenization, stopword removal, etc.)

Extractive summarization

Abstractive summarization using Transformer models

Evaluation using ROUGE metrics

📌 Example Output
Input (Legal Paragraph):

sql

Whereas the party of the first part agrees to lease the premises to the party of the second part for a period of one year...
Generated Summary:

The agreement leases the premises for one year to the second party.
📝 License
This project is released under the MIT License.

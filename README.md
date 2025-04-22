# Proper-Capitalisation-of-Words
# 🧠 Truecasing and POS-based Word Capitalization using StanfordNLP

This project showcases a text normalization pipeline that transforms raw, lowercase sentences into properly formatted text using NLP techniques. Specifically, it applies **truecasing** (capitalizing the first word of each sentence) and **part-of-speech (POS) based capitalization** using StanfordNLP.

---

## 🔍 What It Does
- Tokenizes a raw paragraph into individual sentences using **NLTK**.
- Applies **truecasing** by capitalizing the first word of each sentence.
- Uses **StanfordNLP**'s multi-word token (MWT) pipeline to:
  - Tokenize and parse each sentence.
  - Identify POS tags like proper nouns (PROPN), verbs (VERB), etc.
- Demonstrates how POS tags can be used to further process or selectively capitalize words in a linguistically informed way.

---

## ✨ Sample Input
```
"i think that john stone is a nice guy. there is a stone on the grass. i'm fat. are you welcome and smart in london?"
```

## ✅ Output (Truecased)
```
I think that john stone is a nice guy. There is a stone on the grass. I'm fat. Are you welcome and smart in london?
```

> The output can further be refined using POS-based rules, which the StanfordNLP pipeline helps facilitate.

---

## 🛠 Tech Stack
- Python 3.x  
- Jupyter Notebook  
- StanfordNLP (Tokenizer, POS Tagger)  
- NLTK (Sentence Tokenizer)

---

## 📦 Setup Instructions
```bash
pip install stanfordnlp
pip install bleu
python -m nltk.downloader punkt
python -m nltk.downloader averaged_perceptron_tagger
python -m stanfordnlp.download en
```

---

## 📚 Use Cases
- Preparing datasets for NLP tasks like machine translation or sentiment analysis.
- Demonstrating linguistic structure and POS tagging in educational contexts.
- Enhancing readability for conversational AI or chatbot responses.

---

## 📖 Reference
- **How To Capitalize Words Using AI** — Michel Kana, Ph.D  
  [https://towardsdatascience.com/how-to-capitalize-words-using-ai-13750444d459](https://towardsdatascience.com/how-to-capitalize-words-using-ai-13750444d459)



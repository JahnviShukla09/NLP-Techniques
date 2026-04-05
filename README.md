# 📊 STUDY OF NLP TECHNIQUES ON TEXT DATA USING PYTHON

Name – Jahnvi Shukla <br/>
Branch – ENTC A3 <br/>
PRN – 25070123055 <br/>

---

## 🎯 Aim

To study and perform **basic NLP (Natural Language Processing) techniques using Python and NLTK library**.

---

## 📘 Introduction

Natural Language Processing (NLP) is a field of computer science that deals with the interaction between **computers and human language**. It enables machines to understand, interpret, and process text data.

Text data is unstructured in nature, so it needs to be processed and cleaned before analysis. NLP techniques help convert raw text into a structured format.

Python provides powerful libraries like **NLTK (Natural Language Toolkit)** that support various NLP operations such as tokenization, stop word removal, stemming, and more.

---

## 📚 Theory

NLP involves several preprocessing steps to analyze and understand text data effectively.

**Tokenization** is the process of splitting text into smaller units such as words or sentences. It is the first step in text processing.

**Stop word removal** eliminates commonly used words such as "is", "the", and "and" that do not add much meaning to the text.

**Stemming** reduces words to their root form by removing suffixes. For example, "running" becomes "run".

**Lemmatization** converts words into their meaningful base form using vocabulary and grammar rules. It is more accurate than stemming.

**Part-of-Speech (POS) Tagging** identifies the grammatical role of each word in a sentence, such as noun, verb, adjective, etc.

**Word Frequency Analysis** counts how often each word appears in the text. This helps in identifying important words and patterns.

Using these techniques, raw text data can be transformed into meaningful information for analysis.

---

## ⚙️ Procedure

1. Import **NLTK library** in Python.
2. Download required datasets such as punkt, stopwords, and wordnet.
3. Perform **word tokenization** using `word_tokenize()`.
4. Perform **sentence tokenization** using `sent_tokenize()`.
5. Remove stop words using `stopwords.words()`.
6. Apply **stemming** using `PorterStemmer`.
7. Apply **lemmatization** using `WordNetLemmatizer`.
8. Perform **POS tagging** using `pos_tag()`.
9. Analyze word frequency using `FreqDist`.

---

## 📊 Observations / Result

* Text was successfully divided into **words and sentences** using tokenization.
* Stop words like “is”, “the”, “in” were removed.
* Words were reduced to root form using **stemming**.
* Lemmatization produced more meaningful base words.
* POS tagging correctly identified grammatical roles like noun, verb, adjective.
* Word frequency analysis showed the **most commonly used words** in the text.

Final processed text became **clean, structured, and ready for analysis**.

---

## 🛠️ Tools / Libraries Used

* Python
* Google Colab / Jupyter Notebook
* NLTK Library

---

## 💡 Applications

* Text classification
* Chatbots and virtual assistants
* Sentiment analysis
* Search engines
* Language translation

---

## ✅ Advantages

1. Helps in understanding unstructured text data
2. Improves text analysis and processing
3. Removes unnecessary words
4. Extracts meaningful information
5. Widely used in AI and machine learning
6. Enhances automation of language-based tasks

---

## 🏁 Conclusion

NLP techniques are essential for processing and analyzing text data. Using Python and the NLTK library, operations such as tokenization, stop word removal, stemming, lemmatization, and POS tagging can be performed efficiently. This experiment demonstrates how raw text can be transformed into structured and meaningful information.

# 🧠 Statistical Analysis of Norwegian Text

This project explores basic techniques of **statistical language processing (SLP)** applied to Norwegian literary texts.  
It combines linguistic intuition with statistical modeling to analyze and interpret word frequency distributions, lexical diversity, and other quantitative linguistic features.

---

## 📚 Source Texts

Two literary works from **Project Gutenberg** were used as corpora for this analysis:

1. [*Jenny* (1911) by Sigrid Undset](https://gutenberg.org/cache/epub/32245/pg32245.txt)  
2. [*Mogens and Other Stories* (1882) by J.P. Jacobsen](https://gutenberg.org/cache/epub/30027/pg30027.txt)

These texts were chosen because they are **classic examples of early 20th-century Scandinavian prose**, providing a valuable basis for studying lexical frequency, stylistic variation, and historical language use.

---

## 🔍 Overview

Statistical language processing (also known as *statistical NLP*) involves using data-driven, probabilistic methods to represent and study language.  
Key techniques used in this project include:

- Tokenization and frequency analysis  
- Word distribution and Zipf's law visualization  
- Part-of-speech analysis  
- Exploration of high-frequency vs. low-frequency vocabulary  

The project’s goal is to demonstrate how **quantitative linguistic analysis** can reveal structure and tendencies in natural text.

---

## 🧩 Next Development Step: The Swadesh List

An intended next step is implementing a **Swadesh list** comparison — a foundational concept in historical and comparative linguistics.

### 🧭 What is the Swadesh List?

The **Swadesh list** is a set of about 100–200 basic, universal words (like *water*, *sun*, *mother*, *fire*, *hand*, *name*, etc.) that appear in nearly all human languages and change relatively slowly over time.  
It is widely used in:

- **Lexicostatistics** – measuring how closely related two languages are  
- **Glottochronology** – estimating when two languages diverged  

### ⚙️ Challenges

Implementing the Swadesh list computationally involves several non-trivial challenges:

1. **Translation ambiguity** – a single concept may have multiple lexical realizations (*hand* vs. *arm*, *water* vs. *lake*).  
2. **Limited corpora** – older or minor languages often lack standardized, digitized resources.  
3. **Morphological variation** – words occur in many inflected forms, requiring lemmatization or morphological analysis.  
4. **Semantic drift** – meaning changes over time, making direct comparison unreliable.  

To address these issues, future development should include:
- A curated multilingual lexicon aligned with Swadesh entries  
- Morphological normalization (lemmatization)  
- Statistical or semantic alignment for cognate detection  



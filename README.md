# Natural Language Processing

## Installation:
1. Natural Language Toolkit

        python -c "import nltk;nltk.download('all')"

2. Wordcloud Library

        conda install -c conda-forge wordcloud

3. News API Python Client Library

        pip install newsapi-python

4. IBM Watson Python Library

        pip install --upgrade "ibm-watson>=3.0.3"

5. SpaCy Library

        conda install -c conda-forge spacy
        python -m spacy download en_core_web_sm

6. alpaca-trade-api SDK

        pip install alpaca-trade-api

7. python-dotenv Library 

        pip install python-dotenv

## Important Terminologies & Concepts
* **Natural Language Processing (NLP)** is a methods  for building computer software that understands, generates, and manipulates human language.  —Jacob Eisenstein
  
* **Tokenization** is the process of segmenting running text into words, sentences, or phrases.
  
* **Stopwords** are Words that, for analysis purposes, do not have informational content. Words like “the,” “there,” and “in.” they are useful for grammar and syntax, but they don’t contain any important content. 
  
* **Lemmatization** is standardizing the "morphology" of words. For example, walking, walked, and walks will all become walk. 

* **N-Grams** are tokens that include multi-word phrases. The n is the number of words—for example, bigrams are two-word combinations. 

* **Sentiment Analysis** is a field within NLP, it’s defined as “the computational study
of people's opinions, sentiments, emotions, and attitudes.”
   
   *  Polarity (positive, neutral, negative)
   *  Emtions(happy, angery, sad)
   *  Intentions (detects what people want to do)

* **Term Relevance**  is quite important on sentiment analysis since leads to a better understanding of human speech.
* Corpus  is a large, structured and organized collection of text documents that normally verses on a specific matter.
* **TF** Term Frequency
* **IDF** Inverse Document Frequency
* **TF_IDF** A weighting factor intended to measure how importanat a word is to a document in a collection of documents or corpus.
* **TF** drives the score up, but **IDF** will bring it down.
* **VADER Sentiment**  is a tool used to score the sentiment polarity of human speech as positive, neutral or negative based on a set of rules and a lexicon & it generates 4 scores: 
  *  Positive : compound score >= 0.05
  *  Neutral : compound score <= 0.05 & >=-0.05
  *  Negative : compound score <=-0.05
  *  Compound

## IBM Watson Tone Analyzer
Tone Analyzer is a cloud service from IBM Watson that is able to measure the tone of written text. This service is able to analyze tone in English and French conversations and you can used in Python via its API.

## Natural Language Processing Workflow
1. Preprocessing: preparing the text, including ingestion
2. Extraction: get interesting features of the text
3. Analysis: summarize these features
4. Representation: visualize your analysis

## NLTK
* Core functions depend on language models learned from programmed rules
* Accurate
* Intended for educational and prototyping purposes

## spaCy
* Core functions depend on language models learned from tagged text
* Fast and flexible
* Designed specifically for production use
* also provide tools for tokenization & lemmatization
* In comparison to NLTK, spaCy's language models trades off accuracy for speed

In examples, we will be using spaCy for:
1. Part of speech tagging:  where spaCy will categorizing each word in a sentence by its grammatical role in the sentence. 
2. Named Entity Recognition : Extracting named entities, which include proper nouns and other specific types of nouns such as currencies, from a text.
3. Text As Feature : In order to use this data for classification or prediction, we need
to make them features—numerical representations of unstructured text.




# References & Additional Resources:


* [New APIs](https://newsapi.org/)
* [NEW APPIs Documentation](https://newsapi.org/docs/client-libraries/python)
* [Reuters Corpus Documentation](https://www.nltk.org/book/ch02.html#reuters-corpus)
* [nltk.sentiment.vader module](https://www.nltk.org/api/nltk.sentiment.html#module-nltk.sentiment.vader)
* [Tone Analyzer](https://cloud.ibm.com/catalog/services/tone-analyzer)
* [Search Worldwide News Using API](https://newsapi.org/)
* [spaCy Documentation](https://spacy.io/api/annotation#pos-tagging)
* [spaCy Usage Documentation](https://spacy.io/usage)
* [Natural Language Processing with Python Book](https://www.nltk.org/book/)






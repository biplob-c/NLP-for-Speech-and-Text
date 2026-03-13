# NLP-for-Speech-and-Text
Natural Language Processing for Speech and Text: From Beginner to Advanced


# 1. What is Sequences?
- Ordered arrangement of smaller elements, that combine to form a larger unit with meaning.

# 2. Application of NLP in Text?
# Enhanced Functionality:
- Grammar and spellcheckers:
  - Ensure accourate and error-free written communication
  - Grammarly, MS Word, Google Doc etc.

- Plagiarism Detection:
  - Itentified copied content.

- Text Summarization:
  - Condense large volume of text into summaries.
  - News aggregators, research paper summaries.

- Sentiment Analysis:
  - Evaluate the emotional tone behind a body of text.
  - Social media monitoring feedback analysis, to gauge perceptions about products, brands, and services.
 
- Information Retrieval:
  - Find relevant information from large datasets and databases.
  - Search engine, digital libraries.
 
- Document Clustering:
  - Group similar text documents.
  - Research analysis, content recommendation systems
 
- Machine Translation:
  - Text from one language to another.
  - Google translate, Microsoft Translator, communication applications.

# 3. Application of NLP in Speech?
- Automatic speech recognition (ASR).
- Interactive voice response systems (IVR)
- Speech enhancement and noise reduction
- Speech analytics for business intelligence (BI)

# 4. How Computers understand sequences in NLP?
- The core of all NLP technique is - to convert sequences into numerical representations.
- These representations are then processed using classical, machine learning, and deep learning algorithms.

# 5. Text Representation?
['Natural', 'Language', 'Processing', 'for', 'Text', 'and', 'Sppech']
- Natural: 0
- Language: 1
- Processing: 2
- for: 3
- Text: 4
- and: 5
- Speech: 6
  
# 6. Vector?
- Ordered list of numbers.

# 7. One-Hot Vector?
- Natural ---> [1, 0, 0, 0, 0, 0, 0]
- Language ---> [0, 1, 0, 0, 0, 0, 0]
- Processing ---> [0, 0, 1, 0, 0, 0, 0]
- for ---> [0, 0, 0, 1, 0, 0, 0]
- Text ---> [0, 0, 0, 0, 1, 0, 0]
- and ---> [0, 0, 0, 0, 0, 1, 0]
- Speech ---> [0, 0, 0, 0, 0, 0, 1]

# 8. One-Hot Encoding using scikit-learn: 
- See code...
- 
# 9. Text Represenation: N-grams?
- An N-Gram is a continuous sequence of 'n' items from a given sample of text of speech. Such as - Charracters, syllables, or words.

# Types of N-Grams:
- **Unigrams:** ['Natural', 'Language', 'Processing', 'for', 'Text', 'and', 'Sppech']
- **Bigrams:** [('Natural','Language'), ('Language', 'Processing'), ('Processing', 'for'), ('for', 'Text'), ('text','and'), ('and', 'Sppech')]
- **Trigrams:** [('Natural','Language','Processing'), ('Language','Processing','for'), ('Processing','for','Text'), ('for','Text','and'), ('text','and','Speech')

# 10. N-Gram representation using NLTK: 
- See code...
- 
# 11. Text Representation: Bag of Words (BoW)
- A text representation technique in which text is converted to numbers according to the frequency of tokens.
- Ignores order and context.
- Dissimilar sentences represented as the same.
- E.g:
  - Natural Language Processing for Speech and Text.
  - Language Processing for Natural Speech and Text.
  - Text and Speech for Natural Language Processing.
    - Natural(1), Language(1), Processing(1), for(1), Speech(1), and(1), Text(1)
    - 
# 12. Bag-of-Words using scikit-learn: 
- See code

# 13. TF-IDF (Term Frequency - Inverse Document Frequency): highlights importwn terms
- **TF:** count of terms in document/total terms in document
- **IDF:** log(total number of documents/number of documents containing term)

# 14. TF-IDF using scikit-learn:
- see code

# 15. Text Representation Word Embeddings:
- Word embeddings are Dense vector representations capable of encoding both semantic and contextual information from text data.
- In the simplest term, in embedding, words are known by the company that they keep.
- Embedding can be static, where all instances of a word are represented with the same vector.
- Or Dynamic, where words have different vectors if they mean different   things.

# 16. Word2Vec embedding using Gensim:
- See code

# 17. Embedding with pretrained spaCy mode

# 18. Sentence Enbedding using the Sentence Transformers Library:

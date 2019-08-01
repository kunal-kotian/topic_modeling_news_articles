Kunal Kotian, Aug 6, 2018

-------------------
Please review the two notebooks inside the 'notebooks' directory.
The work has been split into text preprocessing (part 1 notebook) and topic modeling (part 2 notebook).


Directory structure:
-------------------

topic_modeling_crunchbase
 |
 |--readme.txt
 |
 |--notebooks
 |   |
 |   |--part_1_text_preprocessing.ipynb
 |   |--part_2_topic_modeling_lda.ipynb
 |
 |--data
 |   |
 |   |--news_corpus_crunchbase.txt.zip
 |
 |--outputs
 |   |
 |   |--lda_5_topics.pkl
 |   |--[other supporting files related to lda_5_topics.pkl]
 |   |--[interactive pyLDAvis visualizations of topics from 5 LDA models]
 |
 |--Data_Science_Project_Crunchbase.pdf


Required Python Packages:
------------------------

** Note:  The code in this assignment is written in Python 3.6.4 **

The following external python packages are required to be installed to run all the code in the Jupyter notebooks:

1. SpaCy
   Installation and download of the English language model:
      pip install spacy
      python -m spacy download 'en'

2. Gensim
   Installation:
      pip install --upgrade gensim

3. Matplotlib
   Installation:
      python -mpip install -U pip
      python -mpip install -U matplotlib

4. Seaborn (Optional)
   Installation:
      pip install seaborn

5. pyLDAvis
   Installation:
      pip install pyldavis

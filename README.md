# topic-modelling-incident-data

Code to implement topic modelling - process of extracting high level topics on service management data to understand pain areas for a particular group.

Process involves:
• Tokenization: Split the text into sentences and the sentences into words. Lowercase the words and remove punctuation.
• Stopwords (the, a, an, in) removal.
      Can listening be exhausting -> Listen
      I like reading so I read-> Like, Reading, Read
• Lemmatization & Stemming: Process of reducing the different forms of a word to one single form.

For doing Topic Modelling:
• LDA (Latent Dirichlet Allocation) statistical model to be used.
• Gensim library to be used for running DA (https://github.com/RaRe-Technologies/gensim)

Visualizing the results:
• Pyldavis to be used for topic modeling visualization (https://www.machinelearningplus.com/nip/topic.
modeling-visualization-how-to-present-results-Ida-models/)

lda.html has been generated using this process which can be further rendered as needed.

Usage notes:

- Install nltk, gensim, numpy, pandas, pyldavis, matplotlib, pyLDAvis.gensim
- git clone https://github.com/rajpaljatin19/topic-modelling-incident-data.git
- cd topic-modelling-incident-data
- python runLDA.py
post this step you would see lda.html file would be generated
- ls -ld lda.html

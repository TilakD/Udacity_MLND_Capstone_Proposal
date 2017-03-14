# Udacity_MLND_Capstone_Proposal
Udacity MLND Capstone Proposal in PDF format

### Proposal: 
Create word vectors from a Mahabharata dataset to extract semantic similarities.

### Domain Background:
According to Wikipedia “Natural language processing (NLP) is a field of computer science, artificial intelligence, and computational linguistics concerned with the interactions between computers and human (natural) languages and, in particular, concerned with programming computers to fruitfully process large natural language corpora.

Challenges in natural language processing frequently involve natural language understanding, natural language generation (frequently from formal, machine-readable logical forms), connecting language and machine perception, managing human-computer dialog systems, or some combination thereof.” The Mahabharata is one of the two major Sanskrit epics of ancient India. The Mahabharata is an epic narrative of the Kurukshetra War and the fates of the Kaurava and the Pandava princes. It also contains philosophical and devotional material, such as a discussion of the four "goals of life" or purusharthas. Among the principal works and stories in the Mahabharata are the Bhagavad Gita, the story of Damayanti, an abbreviated version of the Ramayana, and the Rishyasringa, often considered as works in their own right. 

The Mahabharata is the longest known epic poem and has been described as "the longest poem ever written" Its longest version consists of over 100,000 shloka or over 200,000 individual verse lines (each shloka is a couplet), and long prose passages. About 1.8 million words in total, the Mahabharata is roughly ten times the length of the Iliad and the Odyssey combined, or about four times the length of the Ramayana, which makes it a huge dataset for using NLP.

By utilizing NLP, we can organize and structure knowledge of the huge Mahabharata to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, sentiment analysis and topic segmentation, which will be helpful for extracting quick, short and consise answers.

### Problem Statement: 
In ancient times this knowledge used to pass along generations, but in this fast moving world, everyone needs answers easily and to be in their fingertips. Most of the relationships between characters in lengthy novels are hard to remember for general public, here NLP’s Semantic similarities come into play.

This corpus of data, of about 29100 words will be fed as input to the model to create word
vectors and with the help of NLTK, we would analyze semantic similarities between characters. For
example, Arjuna was the son of Indra- the king of celestials and Krishna was son of Vasudeva. If an
input is given as Arjuna, Indra and Krishan, system should be capable to provide an answer as
Vasudeva, based on the knowledge learnt using NLP.

### Datasets and Inputs:
Dataset is a set 18 text file, where in each text file is Parva (Which means book in Sanskrit).
Below is an image taken from Wikipedia, having information of all 18 books.

Dataset was obtained from an online library, Nitaaiveda. Below is the statistics of the books,
altogether combined.

This corpus of data, of about 29100 words will be fed as input to the model to create word vectors using word2vec and with the help of NLTK, we would analyze semantic similarities between characters.


### Solution Statement:
As described above the corpus of words will be used as an input to create word vectors using word2vec, with the help of t-SNE or PCA reduce the dimensions of the word vectors and finally use cosine similarity to analyze semantic similarities, i.e. to answer relationship questions based on the learning. The end solution of this project will be to analyze relationships and logics in the dataset.

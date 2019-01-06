# Classification using KNN

#### Datasets:
Given dataset contains text rows of medical abstract belonging to 5 classes.

#### Aim:
To develop a KNN classifier for classifying the medical records into 5 classes.

#### Approach:
1)Separate Text data and labels.
2)Tokenise the text,lower case all the text,remove punctuation,stopwords.
3)Lemmatise all the words and perform stemming.
4)Create CSR matrix to store all the text into matrix form for further computation.
5)Normalise the rows using their l2 norm so that cosine similarity between text records just requires dot product.
6)Top K neighbours are chosen and majority vote is taken to assign label.

# PySpark MLLib Introduction and Examples
_Bartley Richardson_  
_16 February 2017_  

Introduction on using MLLib in PySpark created for the NOVA Data Science meetup on 16 February 2017. This notebook contains an example of supervised machine learning (logistic regression) using PySpark MLLib as well as two unsupervised techniques (Word2Vec and _k_-means clustering). Some final analysis and plots have been generated using [Tableau](https://www.tableau.com). In those cases, the images/plots generated in Tableau are available as static images in this repo.

This notebook utilizes Spark 2.x. For those using Spark 1.6.x, some commands will differ.

The [bank marketing dataset](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#) is replicated here and originally provided in the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets.html).

### References and Acknowledgments
Insipriation taken from: https://github.com/jadianes/spark-py-notebooks

Word2Vec example: https://www.tensorflow.org/tutorials/word2vec/

Original Google Word2Vec code: https://code.google.com/archive/p/word2vec/

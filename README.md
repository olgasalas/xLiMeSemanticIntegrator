This readme provides information about dependencies, installation instructions and how to get started with the code.

## Dependencies

Code is Written in Python 2.7+ and Java. Also, it depends on.

* [Numpy](http://www.numpy.org/)
* [Scipy](https://www.scipy.org/install.html)
* [sklearn](http://kafka.apache.org/)
* [gensim](https://radimrehurek.com/gensim/)
* [LangID](https://github.com/saffsd/langid.py)
* [Rake] (https://github.com/aneesha/RAKE)
* [Pymongo-2.8] (https://pypi.python.org/pypi/pymongo/2.8)
* [Kafka Python Client] (https://github.com/dpkp/kafka-python)
* [MongoDB](https://www.mongodb.com/)
* [Apache Kafka](http://kafka.apache.org/)

##  Installation Instructions

1. `git clone https://github.com/adityamogadala/xLiMeSemanticIntegrator.git`
2.  Download Word Embeddings ([Monolingual and Bilingual](http://people.aifb.kit.edu/amo/wordembeddings/)) and keep it in StoreWordVec/wiki for Wikipedia, StoreWordVec/news for News etc..
3.  pip install -r requirements.txt 

##  Get Started

Examples folder contains few examples on how to use different classes for tasks such as simple search, advanced search, monolingual and cross-lingual document similarity and analytics. You can use individual python files or ipython file (.ipynb) for execution.

# CSCE-4205-ML-Project

**Project Name:**

Sentiment Distribution over the 5-Star Ratings Scale

**Participants:**

- Matthew Fredericksen: [MatthewFredericksen@my.unt.edu](mailto:MatthewFredericksen@my.unt.edu)
- Conner Lynch: ConnerLynch@my.unt.edu
- ~~Adil Afroze: AdilAfroze@gmail.com~~

**Workflow:**

All work on this project will be hosted in [this repository](https://github.com/mattfredericksen/CSCE-4205-ML-Project).

We will meet at least weekly (potentially more) in the evenings on discord to discuss
project development or problems. We will use version control via GitHub, and also use
Google Colab notebooks when appropriate to further foster collaboration.

**Project Abstract:**

This project will evaluate reviews from one product category from a large Amazon
product dataset, collected by Jianmo Ni in 2018. We will create a machine learning
model to make a multiclass prediction of the star-rating, based on the text content of the
review. Using this model, we will examine the nature of sentiment distribution across the
5-star ratings scale.

**Project Design and Milestones:**

- Python programming language
- Pycharm and other IDEs
- Libraries
  - SK learn
  - Lots of machine learning models readily available.
  - Pandas
  - Numpy
  - NLTK, SpaCy, or other NLP libraries
    - Lemmatization, tokenization, stop-word removal, and other text
processing functions.
-  Github repository
    - Used for version control and collaboration.
- Google Collab Notebook
  - Used to host the training and testing of our model.


**Milestones**

- Finding a good dataset
- Partitioning training, development, and test sets
- Feature engineering and preparing the data
- Code to train the model
- Code to test the model
- Evaluate model accuracy
- Evaluate our model against another baseline model
- Analyze model and results
- Stretch goal: Tune hyperparameters
- Stretch goal: Compare the results of training our model across multiple product
domains (e.g. electronics, books, etc.) with the results of training and testing the
model within one specific product domain.

**Resources and Related Projects:**

- Jianmo Ni, Jiacheng Li, Julian McAuley
    _Empirical Methods in Natural Language Processing (EMNLP)_, 2019  
- [This dataset](https://nijianmo.github.io/amazon/index.html) contains tens of millions of reviews collected from
    products on Amazon. The dataset contains many features, but
    we will be primarily working with the ‘reviewText’ feature, and
    using the ‘overall’ feature (star rating) as our target.  
  - Collab notebooks for working with this data set:  
    - [Shows how to filter out poorly-formatted samples](https://colab.research.google.com/drive/1Zv6MARGQcrBbLHyjPVVMZVnRWsRnVMpV).  
    - [Contains simple examples of working with the dataset](https://colab.research.google.com/drive/12r4KJVbNqjjhiZ6aeiaG809x-Tg5fm8?usp=sharing).

This paper provides the data set itself and some method to process it. In
addition to that, we will aim to test different models other than the
mentioned “Latent-Factor” Model. Specifically we will see how easy it is to
distinguish closely related classes with our chosen models. If our model is
able to accurately predict star ratings, then this indicates a significant shift
in sentiment between classes. If our model struggles to distinguish between
consecutive star ratings, then this indicates a more subtle shift in sentiment.
In other words, we will determine the distribution of sentiment between
different star ratings. We are tentatively looking at comparing the
performance of Bayes and N-gram models. A significant improvement in
model accuracy of N-gram over Bayes would indicate the importance of word
context when making predictions.

.

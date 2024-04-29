# NLP: Predicting recipe ratings with user reviews

This group project intends to explore how text such as users reviews and recipes descriptions can be used to obtain insights into recipes ratings. It accomplishes this by using a data-set is called "**Food.com Recipes and Interactions**" which it was downloaded from [kaggle](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions). It consists of more than 180.000 recipes and 700.000 recipe reviews covering 18 years of user interactions and uploads on the website [Food.com](Food.com) (formerly GeniusKitchen). The following is the table of contents of our project.

## Table of Contents

1.  Importing and preparing the data

2.  Exploratory data analysis

    2.1. Main findings

    2.2. Research Question

3.  Applying unigrams & bigrams and bigrams & trigrams stemming to the users' reviews in order to predict recipes' ratings

    3.1. Users' reviews - LASSO Model for unigrams and bigrams

    3.2. Users' reviews - LASSO Model for bigrams and trigrams

    3.3. Users' reviews - Binary LASSO Model for unigrams and bigrams

    3.4. Users' reviews - Binary LASSO Model for bigrams and trigrams

    3.5. Accuracy Plots

4.  Applying unigrams & bigrams stemming to users' reviews and to recipes' descriptions, steps and ingredients to predict recipes' ratings

    4.1. Recipes' descriptions - LASSO Model for unigrams and bigrams

    4.2. Recipes' Steps - LASSO Model for unigrams and bigrams

    4.3. Recipes' Steps - LASSO Model for unigrams and bigrams

    4.4. Accuracy plots

5.  Benchmarks

    5.1. Word Count and Traditional Sentiment Analysis

    5.2. Positive Sentiment, Negative Sentiment and Uncertainity Sentiment

    5.3. LM Dictionary with Grammar Awareness

    5.4. Plotting the best model with the benchmarks

6.  Transfer learning - training a model on positive reviews to predict negative reviews and vice-versa

7.  Politeness on Review Data

8.  Limitations and improvements

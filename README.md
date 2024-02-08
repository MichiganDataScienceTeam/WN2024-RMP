![header](asset/header.png)

# WN24-RMP

<img src="asset/rmp.jpg" height=50/>

[Rate My Professor](https://www.ratemyprofessors.com) is the biggest platform for student giving feedbacks on professors. It is used by students of different universities around the world. Using the data scraped from the RMP website, we can conduct a lot of interesting analysis that provides insights on our University of Michigan. This project will be mainly split into two parts. The first part will be analyzing the RMP dataset and trying to find answers to some intriguing questions, such as which department of UM has the best overall student feedback on professors. The second part we will dive into conducting sentiment analysis on RMP comments. We will use student comments and labels to train a model for predict a professor’s RMP rating, based on the comments that he receives. We will benchmark our performance and compare our model with an established NLP model that trained on the same or larger dataset and analyze areas of potential improvements.

## Timeline

Subject to changes.
| Date | Activity |
|-----------|------------------------------|
| Feb 11 | Introduction + EDA  📈 |
| Feb 18 | Competition + Intro to Sentiment Analysis 📊|
| Feb 25 | Spring Break  🏝️  |
| March 3 | Spring Break  🏝️|
| March 10 | Deep Dive Sentiment Analysis  🔍 |
| March 17 | Model Designing ⚙️|
| March 24 | Model Training ⬆️|
| March 31 | Model Improvement and Comparison  🔧|
| April 7 | Final Wrap up  📄|
| April 14 | Project Expo 🎉 |

## Technologies

We will be using Python and libraries such as pandas, matplotlib, and scikit-learn. To ensure a consistent
working environment among the team and encourage collaboration, we will write our code on Google Colab. See setup [here](./guide/colab.md)

(If you have your workspace setted up in a different environment ready to go, you are welcomed to use that. However, please note we are trying to spend the minimum time in setup stage, so if issues continue to arise, please use google colab)

## Dataset

In the [data](./data) folder there are four web-scraped csv files. (by Casper Guo). We will be using the cleaned version of them, which are processed and ready to go. [Dataset Schema](./data/info.md)

## Part I - Data Analysis

Feb4 - Feb18

Icebreakers, team assignment. Pandas dataframes, Matplotlib and Seaborn plotting libraries. Basic Python EDA. Competition

## Part II - Sentiment Analysis

March 10 - March 31

Rule-based approach, machine learning approach. NLTK, Transformers, custom model, model comparison.

## Final Demo

April 7 - April 14

Project Expo presentation with streamlit, report paper, slides, or webapp.

## Working with this Repo

We will communicate our weekly goals through this repository. It will be updated before every work session including starter codes, guides, and presentation slides. It will also include the team's solution codes and progress. To add to the repository, fork it and send a pull request.

## Interesting NLP Concepts

[Word Embedding](https://www.turing.com/kb/guide-on-word-embeddings-in-nlp#) How do computers understand and work with English vocabs?

[Vector Embedding](https://www.pinecone.io/learn/vector-embeddings/) Converting and representing objects in high-dimensional vector space.

[SSAT Analogies](https://github.com/Weile-Zheng/word2vec-vector-embedding) Solving SSAT questions with basic vector embedding math operations.

## Other Resources

[Numpy Documentation](https://numpy.org/doc/)

[Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)

[Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

[Scikit-learn Documentation](https://scikit-learn.org/stable/index.html)

[Github Documentation](https://skills.github.com/)

[NLTK Documentation](https://www.nltk.org)

[Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)
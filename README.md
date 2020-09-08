# Text-Classification-Using-BBC-News-Articles

## Text Classification with XGBoost &amp; Others: A Case Study Using BBC News Articles.
Data for this problem can be found from <a href="https://www.kaggle.com/yufengdev/bbc-fulltext-and-category">Kaggle</a>. This dataset contains BBC news text and its category in a two-column CSV format. Let’s see what’s there

In this Note, we will perform different text classification techniques to solve the BBC new article categorization problem. We will also perform a vector space models to represent text data.
## Text cleaning process involves the following steps:
1.Conversion to lowercase. <br>
2.Removal of punctuations. <br>
3.Removal of integers, numbers. <br>
4.Removal of extra spaces. <br>
5.Removal of tags. <br>
6.Removal of stop words (like ‘and’, ‘to’, ‘the’ etc). <br>
7.Stemming (Conversion of words to root form). <br>
<b>I used Python ‘gensim’ library for all text cleaning.<b>
  
 ## Vector Space Modelling & Building the Pipeline
 Vector space modeling is essential for any NLP problem. I used ‘Tf-Idf’.

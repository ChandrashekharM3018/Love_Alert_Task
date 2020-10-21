# Love_Alert_Task

Title:Job Categorizing Model
ABOUT:
Scrape emails from an existing email address on the basis of their subject containing keywords "Thank you for applying" and categorise them into a "job" category.
Emails containing subject label as "Thank you for applying" is collected into a csv file named ScrappedData.csv and with other subject labels are saved as Othersubjects.csv
Both of them are merged into a single csv file named as Mydata.csv.Then a Model is built which filters the JOB category subject contanining mails into a separate csv file named as Filtered.csv
All of these csv files are fed into a folder named Data.

Installations : 
IDE: Jupyter Notebook
This project requires the use of libraries such as SkLearn , pickle, Matplotlib, pandas, numpy,seaborn, Nltk,countvectorizer,TFIDF Transformer.

Run:
In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:
-jupyter notebook JobCategorozingModel.ipynb
This will open the Jupyter Notebook software and project file in your browser.

Dataset:
Emails containing subject label as "Thank you for applying" is collected into a csv file named ScrappedData.csv and with other subject labels are saved as Othersubjects.csv
Both of them are merged into a single csv file named as Mydata.csv.Then a Model is built which filters the JOB category subject contanining mails into a separate csv file named as Filtered.csv
All of these csv files are fed into a folder named Data.


Workflow:
Data is read from the Mydata.csv file.
It has two output labels: Job and Others.
Data Preprocessing and Creating spam wordcloud and ham wordcloud.
Converting the words to vectors using TFIDF Vectorizer, which is a numerical statistic that is intended how to reflect how important a word is to a document in a collection or corpus.
Splitting the dataset into train and test set.
Model is built using various algorithms: SVM, DecisionTree Classifier, Naive Bayes, KNN, Logistic Regression.
Predicting scores for each algorithm.
Filtering the Job Categorized into a new csv file named Filtered.csv
Loading the model to predict and Testing. 
You can Save any model you want using above code.

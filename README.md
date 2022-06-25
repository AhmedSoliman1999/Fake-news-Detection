# Fake-nwes-Detection
The main idea of the project is to detect the news is it real or fake based on data that pre-trained using machine learning models 



Methodology:
To detect the news which is real, and which is fake
First:  we choose the columns that will help us to detect the news.
so, we use the text column as input X and label column is the output column Y as the output is affected only by the text column not any other column as it is the target 
Second:  we remove the punctuation to make text contain only strings and remove stopping word as these words repeated in real and fake data so remove them to have strings that affect the data
Third: use count vectorizer and TFIDF transformer to convert the text to vectors that has value that can be fit after that 
Fourth: fit the data in the model using two Supervised classification models. logistic regression and Linear SVM as we have two category which is real and fake, so we use linear SVM      


- The data set that used: 
The dataset that is used is news.csv file that has data about USA elections 2016 
That has 4 columns The id, title, text, and label 

# NLP-arabicData
This is my first test project with next technoligies that is using an arabic data and a NLP model that's called MultinomialNB(), SVM() and understanding NLP and the processus of NLP and train the model on the arabic dataset and testing it.

I have used two model of machine learning that i have trained to do a classification on my data and i have used TfidfVectorizer(). TfidfVectorizer()  is a method from scikit-learn used for converting text data into numerical TF-IDF (Term Frequency-Inverse Document Frequency) representations, suitable for machine learning algorithms. And i have used model called MultinomialNB() and MultinomialNB() is a Naive Bayes classifier from scikit-learn used for text classification tasks, particularly suitable for discrete features like word counts, which assumes a multinomial distribution for feature probabilities. And another model called SVM() and SVM() (Support Vector Machine) is a powerful machine learning algorithm from scikit-learn used for classification and regression tasks, aiming to find the optimal hyperplane that best separates data points into different classes in a high-dimensional space.

`My steps that i have followed in this solution are:`

`step 1:` i have imported all the necessary libraries like scikit-learn and pandas and re 
 *scikit-learn (sklearn): A comprehensive machine learning library in Python that provides tools for data preprocessing, feature extraction, model selection, and evaluation. It offers implementations of various machine learning algorithms for tasks like classification, regression, clustering, and more.
 *pandas: A Python library that provides easy-to-use data structures, Series and DataFrame, for data manipulation and analysis. It is essential for working with structured data and offers functionalities for data cleaning, filtering, grouping, merging, and more.
 *re: The built-in regular expression library in Python. Regular expressions are powerful tools for pattern matching and string manipulation. The re module allows you to search, match, and replace strings based on specific patterns, making it useful for tasks like text preprocessing, data extraction, and validation, particularly in text processing and NLP tasks.

And i have loaded my data that i am using and it's a random arabic data that i have used.

`step 2:` i have done the preprocessing for the data cuz the data is arabic but got some english letter some links and some emojies so i had to delete all the links and english letter and emojies so that i can use this data to train my model.

`step 3:` in this step i have got a cleaned data for us to use data we have to do some transformation to it like tokenizing it so i have used  TfidfVectorizer() that i have explained before. TfidfVectorizer() is a method from scikit-learn used for converting text data into numerical TF-IDF (Term Frequency-Inverse Document Frequency) representations, suitable for machine learning algorithms. It performs tokenization, calculates word frequencies, and applies IDF re-weighting, preparing the data for NLP tasks like text classification or clustering. 

`step 4:` in this step i have used the train_test_split() model offered by scikit-learn to divide the data into train_data and test_data by the form 80% , 20% .

`step 5:` i have loaded the model that i have used like MultinomialNB() and SVM() models that i have explain before in this documents and trained it .

`step 6:` in this step i have tested my program by giving my model and arabic phrase to predict her class .

`step 7:` i have test the trained model by the testing data and printed the score of the model .

`At the end :` i have created a gradio interface for this NLP program .


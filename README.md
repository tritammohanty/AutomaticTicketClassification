# Automactic Ticket Classification Assignment
> For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base. As an NLP engineer for th financial company I need to automate its customer support tickets system. The financial firm has many products and services such as credit cards, banking and mortgages/loans. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Poblem Statement: To build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue. 
- The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Read the data and made the initial analysis out of it
- Did data cleaning like filtering text, removing missing values & renaming column headers, and preprocessing statistical operations like Lemmatization & POS tagging.
- Found the word count distribution & n-gram distribution. And top 40 words using wordcloud
- Did Topic Modelling and found 5 best clusters. And assigned appropriate classs to them.
- Built Naive Bayes, Logistic regression, Decision Tree, Random Forest models for classifying unclassifed tickets to appropriate classes.
- Logistic regression model was found to be the best model with 93% accuracy on Test Data.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- json - 0.9.25
- numpy - 1.26.4
- pandas - 2.2.2
- regex - 2024.9.11
- nltk - 3.9.1
- spacy - 3.7.6
- seaborn - 0.13.2
- matplotlib - 3.9.2
- scikit-learn - 1.5.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@tritammohanty](https://github.com/tritammohanty) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

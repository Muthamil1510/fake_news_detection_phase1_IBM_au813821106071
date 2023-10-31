# SARANATHAN COLLEGE OF ENGINEERING 
# FAKE NEWS DETECTION USING NLP -  Artificial Intelligence

- [Introduction](#introduction)
  - [Project Overview](#project-overview)
  - [Purpose](#purpose)
- [Literature Survey](#literature-survey)
  - [Existing Problem](#existing-problem)
  - [Problem Statement](#problem-statement)
- [Solution architecture](#solution-architecture)
  -[Empathy map canvas](#empathy-map-canvas)
  -[Ideation and Brainstorming](#ideation-and-brainstorming)
- [Problem solution](#problem-solution)
  - [Data Collection](#data-collection)
  - [Data Processing](#data-processing)
  - [Labelling](#labelling)
  - [data splitting](#data-splitting)
  - [Feature Extraction](#feature-extraction)
  - [Model Selection](#model-selection)
  - [Evaluation](#evaluation)
  - [Continuous Monitoring](#continuous-monitoring)
  - [User Interface](#user-interface)
- [How to run the project](#how-to-run-the-project)
  - [Installation](#installation)
  - [project file](#project-file)
- [Data Flow Diagram:](#data-flow-diagram)
- [Solution and Technical Architecture](#solution-and-technical-architecture)
- [Conclusion](#conclusion)


## Introduction

### Project Overview

In an age of digital information overload, the spread of fake news and misinformation has become a critical issue. This project aims to develop   Fake News Detection system using Natural Language Processing (NLP) techniques. The objective is to create a model that can automatically identify and flag news articles, social media posts, or any textualcontent that contains false or misleading information

### Purpose

* 1.Preserving Information Integrity
* 2.Enhancing Media Literacy
* 3.Aiding Fact-Checking Organizations
* 4.Promoting Accountability
* 5.Preserving Trust in Information Sources
* 6.Mitigating the Spread of Disinformation

## Literature Survey

### Existing Problem

 Fake news, one of the biggest new-age problems has the potential to mould opinions and influence decisions.The proliferation of fake news on social media and Internet is deceiving people to an extent which needs to be stopped.The existing systems are inefficient in giving a precisestatistical rating for any given news claim. Also, the restrictions on input and category of news make it less varied. This paper proposes a system that classifies unreliable news into different categories after computing an F-score. This system aims to use various NLP and classification techniques to help achieve maximum accurac

### Problem Statement

The problem at hand is to develop a fake news detection model using a Kaggle dataset. The objective is to differentiate between genuine and fake news articles based on their titles and text content. This involves utilizing natural language processing (NLP) techniques to preprocess the textual data, constructing a machine learning model for classification, and evaluating the model's performance.

## Solution architecture

### Empathy map canvas
![image](https://github.com/Muthamil1510/example/assets/146314388/9e2e21cf-db83-462c-89a9-32d88c012b80)

### Ideation and Brainstorming 

![image](https://github.com/Muthamil1510/example/assets/146314388/3bb23ef8-21c8-4baa-aaad-af87ce72286e)

## Problem solution

### Data Collection

Collect a large dataset of news articles, including both credible and fake news. The dataset should be diverse and representative.

### Data Processing

Preprocess the text data, including lowercasing, vectorisation, and removing stop words and punctuation.

### Labelling

Manually or semi-automatically label the collected data as either credible or fake news.

### data splitting

Split the dataset into Training,Validation and test sets to evaluate the models performance.

### Feature Extraction

 Use the preprocessed data to extract features for model training
 
### Model Selection

Choose the best-performing model based on validation results.

### Evaluation

  Evaluate the model's performance on the test dataset to assess its ability to detect fake news accurately.
  
### Continuous Monitoring

  Continuously monitor the system's performance and retrain the model as new data becomes available.
  
### User Interface

Develop a user-friendly interface for users to submit news articles and receive fake news detection results.

## How to run the project

### Installation

You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

```bash
pip install notebook
```
#### project file
* project file is attacted 
* after installing the jupyter notebook, run the code in it
## Data Flow Diagram

![image](https://github.com/Muthamil1510/example/assets/146314388/e82d1572-61fd-4c33-b68f-cd571322b1d6)

* 1.Start: The process begins here.
* 2.Input Text: The input to the system is the news article or text that needs to be checked for authenticity.
* 3.Preprocessing:
   * Text Cleaning: Remove any irrelevant characters, punctuation, and special symbols.
   * Tokenization: Split the text into individual words or tokens.
   * Stopword Removal: Eliminate common words that do not carry much meaning (e.g., "the," "is," "and").
* 4.Feature Extraction:
   * Extract features from the preprocessed text. These features might include word frequencies, TF-IDF scores, or n-grams.
* 5.Machine Learning Model:
  * This is a simplified step. In a real-world scenario, this would be a machine learning or deep learning model trained on labeled data.
  * The model takes the extracted features as input and classifies the news as either "Real" or "Fake."
* 6.Prediction:
  * The model makes a prediction regarding the authenticity of the news.
  * If the prediction score is high for "Real," the news is classified as real;if the score is high for "Fake," it's classified as fake.
* 7.Output:
  * Display the prediction result, indicating whether the news is "Real" or "Fake."
* 8.End: The process ends here.

## Solution and Technical Architecture

![Screenshot (126)](https://github.com/Muthamil1510/example/assets/146314388/e62aef5b-f0be-4ddb-a3fe-a29202c50ae8)

## Conclusion

The passive-aggressive classifier performed best here and gave an accuracy of 93.12%. We can print a confusion matrix to get an overview of the number of true and false positives and negatives. fake news detection techniques can be divided into style- and content-based or fact-checking techniques.  It is often assumed that poor writing (poor spelling, poor punctuation, limited vocabulary, overused terminology, incorrect grammar, etc.) is a sure sign of fake news.  More than ever, this is the case  when a machine's opinion must be supported by clear and  fully verifiable indications on which to   base its decisions, within the events have been  verified and the competent authority determines the authenticity of each event. Collecting  data once  will not be enough given the rapid spread of information in today's connected world and the number of articles produced.  I hope this was helpful to you. You can comment in the comments section for any questions.
## Contact details
Email id: saravananmuthamil@gmail.com



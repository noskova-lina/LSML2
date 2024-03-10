# LSML2

## Project Overview
In this project, I am developing a machine learning service that automatically generates tags for StackOverflow questions. This task involves processing text data, classifying it, and using machine learning techniques to automatically label questions based on their content.

### Objective: 
To predict tags for StackOverflow questions using their text content.

### Data:
Dataset with StackOverflow questions, available on Kaggle: https://www.kaggle.com/datasets/muhammedabdulazeem/500k-stackoverflow-questions/data. This dataset contains questions, answers, and tags associated with the questions. For this task, I only use questions and their associated tags.

### Input: 
Text of a StackOverflow question (both title and body).

### Output: 
List of tags most relevant to the question.

## Key Components:

Data Exploration and Preprocessing: I start with a dataset comprising 500k StackOverflow questions, each with associated tags. The preprocessing steps include cleaning text, tokenization, and transforming tags into a format suitable for multi-label classification.

Model Training with Transfer Learning: Leveraging BERT, a pre-trained transformer model renowned for its effectiveness in NLP tasks, I fine-tune it for the specific tag prediction task. This approach allows to benefit from BERT's understanding of language nuances without the need for extensive computational resources.

MLOps Integration: The project incorporates MLOps practices to streamline the machine learning workflow. I use MLflow for experiment tracking, allowing to log parameters, metrics, and models. For a more comprehensive overview, Neptune.ai is utilized, offering advanced experiment tracking and visualization capabilities.

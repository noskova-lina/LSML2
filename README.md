# LSML2

## Project Overview
In this project I develop a machine learning service to automatically generate tags for StackOverflow questions. Utilizing the power of natural language processing (NLP) and the state-of-the-art BERT model for transfer learning, the service processes the text of StackOverflow questions to predict relevant tags, facilitating efficient categorization and searchability.

Objective: To accurately predict tags for StackOverflow questions using their text content.

Input: Text of a StackOverflow question (both title and body).

Output: A list of predicted tags relevant to the question.

## Key Components:

Data Exploration and Preprocessing: I start with a dataset comprising 500k StackOverflow questions, each with associated tags. The preprocessing steps include cleaning text, tokenization, and transforming tags into a format suitable for multi-label classification.

Model Training with Transfer Learning: Leveraging BERT, a pre-trained transformer model renowned for its effectiveness in NLP tasks, I fine-tune it for the specific tag prediction task. This approach allows to benefit from BERT's understanding of language nuances without the need for extensive computational resources.

MLOps Integration: The project incorporates MLOps practices to streamline the machine learning workflow. I use MLflow for experiment tracking, allowing to log parameters, metrics, and models. For a more comprehensive overview and collaboration, Neptune.ai is utilized, offering advanced experiment tracking and visualization capabilities.

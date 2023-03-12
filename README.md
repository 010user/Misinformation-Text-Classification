# Misinformation-Text-Classification
The objective of this project is to create a machine learning model that can effectively differentiate between authentic news and fake news in news articles. This is achieved by analyzing different aspects of the content. Through this analysis, the model can automatically recognize news articles that contain deceptive or inaccurate information.

## Table of Contents
- Installation
- Usage
- Data
- Methodology
- Results
- Conclusion

## Installation 
To run the project, you will need Python 3.7 or higher and the following packages:
- pandas
- numpy
- sklearn
You can install these packages using pip command in python e.g.
![image](https://user-images.githubusercontent.com/53361804/224561696-9dfc3d92-0d04-47bf-9cf7-44554a14ed54.png)

## Usage
To run the code, simply clone the repository and run the main script.

## Data
The data used in this project comes from the Kaggle Dataset (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## Methodology
The project follows the following methodology:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature selection and engineering
- Model selection and training
- Model evaluation

### TF-IDF Vectorizer
- TF-IDF Vectorizer is a feature extraction technique used in machine learning for text data.
- It converts the textual data into a matrix of numerical features that can be easily understood and processed by machine learning models.
- First it tokenizes the text data into individual words, then calculating the term frequency (TF) and the inverse document frequency (IDF) for each word in each document. 
- The TF measures the frequency of a word in a single document, while the IDF measures the importance of a word across all documents in the dataset. By multiplying these two values together, the algorithm produces a score for each word in each document.

## Results
The project achieves a high accuracy of 93.37% in predicting whether a news article is fake or not.

## Conclusion
To summarize, the fake news detection project successfully developed a machine learning model that accurately distinguishes between genuine and fake news articles. The project has significant implications for addressing the growing concern of fake news and can be integrated into news analysis tools to help users make informed decisions based on accurate information.

# Practical-Task-AI-Engineer
AI Engineer Task - Sentiment Analysis and Topic Modeling

# Overview
This project performs sentiment analysis and topic modeling on a dataset containing feedback for various AI courses. It aims to understand the sentiments and common themes in the feedback to drive actionable insights.

# Features
Data Preprocessing: Text cleaning, tokenization, stop-word removal, etc.
Sentiment Analysis: Using NLTK's VADER Sentiment Intensity Analyzer.
Topic Modeling: Utilizing Latent Dirichlet Allocation (LDA) to identify common topics.
Opinion Mining: Extracting specific opinions and attitudes.
Insights and Recommendations: Providing actionable insights and recommendations.
Report Generation: Creating a comprehensive PDF report summarizing the findings.

# Requirements

Python 3.x
Jupyter Notebook
NLTK
Pandas
Scikit-learn
Matplotlib
Spacy

# Installation
Run the following commands to set up the environment:

    pip install pandas nltk scikit-learn matplotlib spacy openpyxl

# Then, download the necessary NLP resources:

    import nltk
    nltk.download('vader_lexicon')
    nltk.download('stopwords')
    nltk.download('wordnet')
    nltk.download('punkt')

# Running the Notebook
Clone the repository.
Navigate to the project directory and launch Jupyter Notebook.
Open the .ipynb file.
Run all the cells in the notebook.
Structure of the Notebook
Initial Setup and Data Conversion: Converts data from Excel to CSV.
Data Preprocessing: Cleans and prepares the text data.
Sentiment Analysis: Determines the sentiment of each feedback.
Topic Modeling: Identifies the most common topics in the feedback.
Opinion Mining: Extracts specific opinions and attitudes.
Insights and Recommendations: Human-based insights and action points.
Comprehensive PDF Report Generation: Generates a PDF summarizing the analysis.
Documentation: Comments and markdown cells explaining the code.


# License
This project is licensed under the MIT License.

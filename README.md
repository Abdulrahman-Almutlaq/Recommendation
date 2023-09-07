# Starbucks Recommendation System

This project aims to develop a recommendation system for Starbucks offers based on user behavior and preferences. Three recommendation algorithms were implemented: Rank-Based Recommendations, User-User Based Collaborative Filtering, and Matrix Factorization. User-User Based Collaborative Filtering was chosen as the final recommendation method due to its superior performance.

# Project Structure
* Starbucks_Capstone_notebook.ipynb: Contains the code for data preprocessing, algorithm implementation, and evaluation.

* data: The data folder contains the Starbucks data used for the project, including portfolio.json, profile.json, and transcript.json.

* transcript_checkpoint.csv: A checkpoint of the data is saved. The production of this data can take some time, thus the code cell that produces this data has been commented.

# Installation
To run the code in the notebook, you'll need to download the required libraries using:
**pip install - r requirements.txt**

Execute the code cells in the notebook sequentially to perform data preprocessing, implement the recommendation algorithms, and test the recommendation yourself!

Detailed explanations and comments are provided within the notebook to guide you through the project.

The final recommendation system, User-User Based Collaborative Filtering, is presented with insights and evaluation metrics.
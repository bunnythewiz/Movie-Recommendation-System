# Movie Recommendation System
![image](https://github.com/user-attachments/assets/98c6695b-93d2-4045-bcf3-8280a016de13)
![image](https://github.com/user-attachments/assets/dd8ead13-c0a0-4459-9c6a-f88418cf15c5)



## Overview
This repository implements a movie recommendation system utilizing various algorithms, including content-based and item-based collaborative filtering. The project includes data exploration, preprocessing, feature extraction, and model training.
- Project-Page -> [Click Here](https://vaibhav92735.github.io/Movie_Recommendation_App/)



## Project Structure

### EDA and Preprocessing
- **`EDA_Preprocessing_and_Feature_Extraction/`**: Contains notebooks for exploratory data analysis, primary preprocessing, and feature engineering.
  - **`EDA_and_Primary_Pre-Processing.ipynb`**: Notebook for exploratory data analysis and initial data cleaning.
  - **`Feature_Engineering.ipynb`**: Notebook for extracting and transforming features necessary for model training.

### Models
- **`Models/`**: Contains notebooks implementing different recommendation algorithms.
  - **`Content_Based_Collaborative_Filtering/`**
    - **`Classical_ML_Models.ipynb`**: Notebook implementing classical machine learning models for content-based filtering.
    - **`NLP_based_Bag_of_Words.ipynb`**: Notebook implementing the Bag of Words model for text-based recommendations.
  - **`Item_Based_Collaborative_Filtering/`**
    - **`Item_Based_Collaborative_Filtering.ipynb`**: Notebook implementing item-based collaborative filtering.

### Data
- **`Raw_Data/`**: Contains the initial datasets used in the project.
  - **`links.csv`**: Dataset containing links to movie information.
  - **`movies.csv`**: Dataset with details of the movies.
  - **`ratings.csv`**: Dataset containing user ratings for the movies.
  - **`tags.csv`**: Dataset with user-generated tags for the movies.
- **`Processed_Data/`**: Contains processed datasets after cleaning and feature extraction.
  - **`Featured Data.csv`**: Dataset containing the features extracted for model training.
  - **`Pre-Processed Data.csv`**: Dataset after primary preprocessing steps.

### Reports
- **`Reports/`**: Contains generated reports documenting the analysis and models used.
  - **`Report_EDA_Pre-Processing.pdf`**: A detailed report on the exploratory data analysis and preprocessing steps.
  - **`Report_Models.pdf`**: A report summarizing the model implementations and evaluations.

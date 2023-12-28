# SmartCourse: Guiding Your Academic Journey - Course Recommendation System

## Inroduction

This project focuses on building a Course Recommendation System using the Udemy Dataset. The primary goal is to enhance the educational experience for users by providing personalized course recommendations based on their preferences and historical interactions. The system employs algorithms such as Cosine Similarity and Linear Similarity to generate accurate and diverse recommendations.

## Installation and Setup

To set up the project on your local machine, follow these steps:

### Codes and Resources Used:

Python Version: Python 3.8

### Python Packages Used:
### General Purpose:
Flask==1.1.1

gunicorn==19.9.0

itsdangerous==1.1.0

Jinja2==2.10.1

MarkupSafe==1.1.1

Werkzeug==0.15.5

jsonschema==3.2.0

neattext>=0.1.2

### Data Manipulation:
numpy>=1.9.2

scipy>=0.15.1

scikit-learn>=0.18

pandas>=0.19

### Data Visualization:
matplotlib>=1.4.3

seaborn>=0.9.1

## Data

### Source Data:

Udemy Dataset: [Link to the Dataset](https://github.com/parthshah28/Course_Recommendation_System/blob/main/udemy_course_data.csv)

Description: This dataset encapsulates a comprehensive overview of Udemy courses, encompassing essential attributes such as course identifiers, titles, URLs, payment status, pricing information, subscriber counts, review statistics, lecture counts, difficulty levels, content durations, and publication timestamps. Additionally, it includes details like subject categories, profit generated from paid courses, and the breakdown of publication dates. This rich dataset is a valuable resource for conducting exploratory analyses, identifying trends within the Udemy platform, and potentially informing the development of recommendation systems to enhance the user experience on online learning platforms.

### Data Preprocessing and EDA:

Preprocessing steps involved in cleaning and organizing the data are detailed in the 'EDA on UdemyDataset.ipynb' notebook.

## Results and Evaluation

The project results, including metrics and visualizations, are presented in the 'data_analysis.ipynb' notebook. Evaluation methodologies and model quality assessments are explained in detail.

## Future Work

Potential future work includes expanding the recommendation system's capabilities, incorporating more advanced algorithms, and refining the user experience. 

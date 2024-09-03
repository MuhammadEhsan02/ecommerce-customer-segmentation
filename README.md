# Predictive Modeling on Customer Segmentation in E-Commerce

This repository is dedicated to my final year project, "Predictive Modeling on Customer Segmentation in E-Commerce," which was conducted as part of the UGD in Artificial Intelligence at NED University of Engineering and Technology.

## Project Overview

The objective of this project is to segment customers within an e-commerce environment based on their purchasing behavior using a combination of machine learning models and natural language processing (NLP) techniques. This project addresses a critical business need by enabling the identification of key factors influencing customer satisfaction and predicting customer review ratings. These insights can be leveraged by businesses to optimize their marketing strategies and enhance overall customer experience.

### Key Features:

1. **Comprehensive Analysis**:
   - A detailed exploration of customer behavior through data cleaning, feature engineering, and exploratory data analysis (EDA).

2. **Predictive Modeling**:
   - Implementation of various machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forests, Adaptive Boosting, XGBoost, Gaussian Naive Bayes, LightGBM, and CatBoost.

3. **Natural Language Processing (NLP)**:
   - Utilization of NLP techniques to analyze customer review texts, extracting sentiments and correlating them with overall satisfaction.

4. **Customer Segmentation**:
   - Application of RFM (Recency, Frequency, Monetary) Analysis and K-means clustering to categorize customers into distinct segments based on their purchasing behavior.

5. **Interactive GUI**:
   - A user-friendly Streamlit-based graphical user interface (GUI) is included, enabling users to interactively explore customer segments and insights derived from the models.

## Contents

1. **Jupyter Notebook**:
   - `Customer_Segmentation.ipynb`: This notebook contains the entire analysis workflow, from data preprocessing to model training and evaluation.

2. **GUI Application**:
   - `gui/`
     - `GUI.py`: A Python script built using Streamlit to provide an interactive user interface for exploring the results.
     - `Clustering_Sample.csv`: Sample data used within the GUI for demonstrating clustering techniques.
     - `EDA.csv`: Dataset utilized in exploratory data analysis, showcased in the GUI.

3. **Pre-trained Models**:
   - `Brazilian_Ecommerce_Classification.pkl`: Pre-trained classification model based on customer reviews.
   - `Brazilian_Ecommerce_Clustering.pkl`: Pre-trained clustering model for segmenting customers.

4. **Requirements**:
   - `requirements.txt`: This file contains a list of Python dependencies required to run the project seamlessly.

## Dataset

The dataset employed in this project, sourced from Olist Shops in Brazil, is too large to be included in this repository. You can access the full dataset here: [Brazilian E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Methodology

The project follows a structured methodology, starting with data acquisition and cleaning, followed by exploratory data analysis to identify patterns and trends. Feature engineering was employed to create new features, and various machine learning models were trained to predict customer satisfaction. Additionally, NLP techniques were used to analyze textual data from customer reviews, providing deeper insights into customer sentiments.

### Key Steps:

- **Data Cleaning**: Addressing missing values, outliers, and inconsistencies.
- **Feature Engineering**: Creating new variables that capture important aspects of customer behavior.
- **Exploratory Data Analysis (EDA)**: Visualizing and summarizing data to uncover patterns.
- **Model Training**: Applying and tuning machine learning models to predict customer satisfaction.
- **NLP Analysis**: Analyzing review text to extract sentiment and correlate it with overall ratings.
- **Customer Segmentation**: Using RFM analysis and clustering to group customers into meaningful segments.

## Future Work

Once my thesis is officially published, this repository will be updated to include the publication along with any new findings or improvements made to the models. The publication will provide a detailed explanation of the methodologies and insights gained from this project.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MuhammadEhsan02/ecommerce-customer-segmentation.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Explore the Notebook**:
   - Open and run the `Customer_Segmentation.ipynb` Jupyter notebook for a complete walkthrough of the analysis.

4. **Run the GUI Application**:
   - Navigate to the `gui` folder and run the Streamlit app:
   ```bash
   streamlit run GUI.py
   ```

## Conclusion

This project demonstrates how machine learning and NLP techniques can be applied in an e-commerce setting to understand and predict customer behavior. The insights generated can help businesses enhance customer satisfaction, optimize marketing efforts, and ultimately drive growth.

## Contact

For any inquiries or further collaboration, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/muhammad--ehsan).

--- 

<h3 align="center">Show some ❤ by <img src="https://imgur.com/o7ncZFp.jpg" height=25px width=25px> this repository!</h3>

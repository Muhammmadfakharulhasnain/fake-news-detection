# **Fake News Detection**

## **Project Overview**

This repository contains a machine learning pipeline for detecting fake news articles. The project involves data preprocessing, feature extraction using TF-IDF, and model training with various classification algorithms including Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest. The repository also includes detailed performance evaluations, visualizations, and tools for manual testing of news articles.

## **Data Details**

### **Datasets Used**
- **Fake News Dataset:** Contains news articles that have been labeled as fake. The data is pre-processed to remove unnecessary features such as titles, subjects, and publication dates.
- **True News Dataset:** Contains news articles that have been labeled as real. Similar preprocessing steps are applied to this dataset.

### **Data Preprocessing**
- **Text Cleaning:** Includes lowercasing, removing punctuation, URLs, and irrelevant symbols.
- **Data Splitting:** The dataset is split into training and testing sets with a 75-25 ratio.

## **Feature Extraction**

- **TF-IDF Vectorization:** Converts the textual data into numerical features that capture the importance of each word in the context of the entire dataset.

## **Models Used**

### **1. Logistic Regression**
- A basic yet powerful algorithm for binary classification tasks, used as a baseline model in this project.

### **2. Decision Tree**
- Provides interpretability by generating decision rules that can easily be visualized.

### **3. Gradient Boosting**
- A more complex model that combines weak learners to improve predictive performance.

### **4. Random Forest**
- An ensemble method that aggregates predictions from multiple decision trees to enhance accuracy.

## **Model Evaluation**

- **Accuracy:** Measures the percentage of correct predictions.
- **Precision, Recall, and F1-Score:** Provide a more detailed understanding of model performance.
- **Confusion Matrix:** Visualizes the performance of the models by showing the true positives, false positives, true negatives, and false negatives.

## **Visualizations**

- **Class Distribution:** Visualizes the proportion of fake vs. real news in the dataset.
- **Top Terms by TF-IDF Score:** Highlights the most significant terms in the dataset.
- **Confusion Matrix:** Provides a visual summary of classification performance.
- **Model Comparison:** Compares the performance of different models side-by-side.

## **Manual Testing**

A utility function is provided to manually test new news articles. This function allows users to input a news article and obtain predictions from all trained models, providing a quick way to assess the reliability of the news.

## **Contributors**

- **[Muhammad Fakhar ul Hasnain]**
  - **Role:** Project Lead, Data Scientist
  - **Responsibilities:** Data Preprocessing, Feature Extraction, Model Training, and Evaluation
  - **Contact:** [muhammmadfakharulhasnain6@gmail.com]

## **Installation and Usage**

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fake-news-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### **Usage**

1. Preprocess the data by running the preprocessing script.
2. Train the models using the training script provided.
3. Evaluate the models using the evaluation script.
4. Use the manual testing tool to test new articles.


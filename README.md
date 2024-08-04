# Ecommerce Product Categorization

## Description
This project was developed as part of a Data Science Hackathon to address the challenges of categorizing products in an ecommerce setting. Accurate product categorization is essential for improving customer experiences, reducing search friction, and enhancing product discoverability.

## Objectives
The key objectives of the project were:
- Data Exploration and Preparation
- Descriptive Analysis
- Feature Engineering/Text to Features
- Predictive Modeling
- Fine Tuning
- Enhancing Categorization Accuracy

## Features
- **Data Exploration and Preparation**: Understand key features, detect missing data, and handle inconsistencies.
- **Descriptive Analysis**: Identify data patterns and category distributions, visualize insights using word clouds and other techniques.
- **Feature Engineering**: Convert text descriptions into numerical features using techniques like TF-IDF and word embeddings.
- **Predictive Modeling**: Develop machine learning and deep learning models for product categorization.
- **Model Evaluation**: Evaluate models using metrics such as accuracy, F1 score, precision, and recall.
- **Comparison of Models**: Compare the performance of machine learning and deep learning models, highlighting that machine learning models provided better accuracy for this task.

## Steps Involved

### Exploratory Data Analysis (EDA)
An in-depth analysis of the dataset was conducted to understand its structure and characteristics. Visualizations were created to identify trends, distributions, and patterns within the data.

### Text Normalization
Text normalization techniques were applied to both the training and test data. Techniques included:
- Converting text to lowercase
- Removing whitespace, punctuation, emojis, and special characters
- Lemmatization
- Removing stopwords
- Handling HTML tags and hyperlinks
- POS Tagging

The `text_normalizer` function was used to preprocess the text data.

### Text Vectorization
Text data was vectorized using TF-IDF vectorization. Both the training and test data were transformed into TF-IDF matrix representations.

### Model Training
Nine machine learning models were trained to classify products into predefined categories. The RidgeClassifier performed particularly well.

### Hyperparameter Tuning
Hyperparameters of the best performing model were fine-tuned to optimize performance.

### Evaluation
The trained model was evaluated on unseen data to assess its performance. An accuracy of 85% was achieved.

### Streamlit Web Application
A Streamlit web application was developed to allow users to input product descriptions and classify them into relevant categories.

## Usage
To use this repository, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Ecommerce-Product-Categorization.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Ecommerce-Product-Categorization
    ```
3. Install the necessary dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook and run the cells to reproduce the results:
    ```sh
    jupyter notebook Ecommerce_Product_Categorization.ipynb
    ```

## Conclusion
This project demonstrates the process of developing an accurate and efficient text classification model for ecommerce product categorization. By addressing the challenges and optimizing the models, this project aims to improve customer experience and product discoverability in the ecommerce domain.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This project was created as part of a Data Science Hackathon.
- Special thanks to the organizers and participants of the hackathon for their contributions and support.


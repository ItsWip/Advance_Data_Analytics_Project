TikTok Video Classification Project

## Project Overview
This project focuses on building a machine learning model to classify TikTok videos based on whether they contain a factual claim or a personal opinion. The objective is to help TikTok efficiently handle user reports and mitigate misinformation by prioritizing flagged content.

## Data Description
The dataset used for this project contains the following key attributes:
- **Video Text Data**: Transcriptions or captions from videos.
- **User Engagement Metrics**: Likes, shares, and comments on each video.
- **Video Duration**: Length of the video.
- **Sentiment Score**: Computed sentiment polarity of the video’s content.
- **Claim Label**: Target variable indicating whether the video presents a factual claim (1) or an opinion (0).

## Approach and Methodology
### 1. Data Preprocessing
- **Text Cleaning**: Removed stopwords, punctuation, and special characters.
- **Feature Engineering**: Extracted meaningful textual features using TF-IDF and word embeddings.
- **Data Balancing**: Addressed class imbalances using resampling techniques.

### 2. Exploratory Data Analysis (EDA)
- **Word Frequency Analysis**: Identified common words used in claim vs. opinion videos.
- **Engagement Trends**: Analyzed how user interactions vary between claim and opinion videos.
- **Sentiment Distribution**: Explored sentiment differences in both categories.

### 3. Model Development
Two primary approaches were explored:
#### a) Traditional Machine Learning Models
- **Logistic Regression**: Established a baseline model.
- **Support Vector Machine (SVM)**: Improved classification with a margin-based approach.
- **Random Forest**: Used ensemble learning to enhance prediction accuracy.

#### b) Deep Learning Model
- **Recurrent Neural Networks (RNN)**: Implemented an LSTM-based text classifier for sequential data processing.
- **Fine-Tuned Pretrained Transformer Model**: Leveraged models like BERT for enhanced text classification.

### 4. Model Evaluation
- **Confusion Matrix**: Analyzed classification performance.
- **Precision, Recall, F1-score**: Measured accuracy and effectiveness.
- **ROC-AUC Score**: Assessed model robustness in distinguishing claim vs. opinion videos.

## Key Findings
- Videos classified as **claims** tend to have more structured language and factual keywords.
- **Opinion videos** exhibit higher sentiment polarity and subjective expressions.
- Machine learning models performed well, with **SVM and BERT-based models achieving the highest accuracy**.

## Tools & Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, TensorFlow
- **Machine Learning Models**: Logistic Regression, SVM, Random Forest, LSTM, Transformers
- **Jupyter Notebook**: For development and documentation

## Next Steps
- Deploy the model in a real-time video moderation system.
- Explore multimodal classification by incorporating audio and visual features.
- Continuously improve model accuracy through active learning and user feedback.




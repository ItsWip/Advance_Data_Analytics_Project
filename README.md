# Advance_Data_Analytics_Project

# TikTok Content Moderation Enhancement Project

This project is part of the Google Advanced Data Analytics Professional Certificate program. It focuses on developing a predictive model to assist TikTok's content moderation team in efficiently classifying user-reported videos as "claims" or "opinions."

## Project Overview

TikTok receives a vast number of user reports daily, making it challenging to promptly identify videos requiring moderation. The objective of this project was to analyze existing data and build a model that predicts the nature of reported videos, thereby streamlining the moderation process.

## Repository Structure

The repository is organized as follows:

- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Jupyter notebooks detailing each phase of the project.
- **scripts/**: Python scripts for data processing and model implementation.
- **reports/**: Generated reports and visualizations from the analysis.
- **README.md**: Project overview and instructions.

## Data Exploration and Cleaning

Initial steps involved importing the dataset and examining its structure. Key activities included handling missing values and engineering features such as engagement metrics (likes, comments, shares per view) to enrich the dataset.

## Statistical Analysis

Hypotheses were formulated to understand relationships between variables. For instance, t-tests were conducted to assess the impact of author verification status on video view counts, revealing that verified authors generally had higher view counts.

## Predictive Modeling

A logistic regression model was first implemented to classify videos, followed by advanced models like Random Forest and XGBoost to capture complex patterns. These models underwent cross-validation and hyperparameter tuning to enhance performance, achieving over 99% accuracy.

## Key Insights

- **Video Length**: Longer videos were more likely to be classified as claims, suggesting that in-depth content often contains factual assertions.
- **Author Verification**: Verified authors tended to have higher view counts, indicating a trust factor influencing audience engagement.
- **Model Performance**: Advanced models significantly improved content moderation efficiency with high accuracy.

## Conclusion

This project demonstrates the application of advanced data analytics techniques to enhance TikTok's content moderation process. By developing robust predictive models, the moderation team can prioritize and address user-reported videos more effectively.

*Note: This project is based on a fictional scenario developed for educational purposes as part of the Google Advanced Data Analytics Professional Certificate program.*

## Getting Started

To explore the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/tiktok-content-moderation.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd tiktok-content-moderation
   ```
3. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter notebooks** located in the `notebooks/` directory to reproduce the analysis and models.

## Dependencies

- Python 3.8 or higher
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- jupyter

Ensure all dependencies are installed to successfully run the notebooks and scripts.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Gratitude to the Google Advanced Data Analytics Professional Certificate program for providing the framework and resources for this project.

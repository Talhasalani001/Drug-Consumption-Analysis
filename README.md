# Drug-Consumption-Analysis

## Project Overview
This project explores patterns in drug consumption using the **Drug Consumption (quantified)** dataset from the UCI Machine Learning Repository. Our objective is to predict drug usage based on demographic and personality metrics, identify clusters of drug users, and analyze the factors influencing drug consumption patterns. The project applies machine learning techniques for classification and clustering to uncover actionable insights into drug usage behaviors.

## Dataset
- **Source**: [Drug Consumption (quantified) dataset](https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified)
- **Description**: The dataset contains 1,885 records with attributes such as:
  - **Demographics**: Age, gender, education, ethnicity, and country.
  - **Personality Traits**: Neuroticism, extraversion, openness, agreeableness, conscientiousness.
  - **Drug Usage**: Consumption frequencies for 18 substances (e.g., alcohol, cannabis, cocaine) categorized into 7 levels.

## Key Questions
1. **Predictive Modeling**: Can we predict cannabis usage based on demographic and psychological metrics?  
2. **Clustering Analysis**: Can we identify groups of individuals based on personality traits and drug consumption patterns?

## Methods
- **Data Preprocessing**:
  - Converted categorical variables to numerical values.
  - Normalized continuous features for comparability.
  - Created binary labels for specific classification tasks.
- **Machine Learning**:
  - Predictive Modeling: Implemented a K-Nearest Neighbors (KNN) classifier for cannabis usage prediction.
  - Clustering: Applied K-Means clustering with the Elbow method to determine optimal clusters.

## Results
1. **Classification**: Achieved ~80% accuracy in predicting cannabis usage with KNN.
2. **Clustering**: Identified distinct clusters based on personality traits and drug consumption, offering insights into shared usage patterns among individuals.

## Team Members
- Varun Singh ([singhva@bc.edu](mailto:singhva@bc.edu))
- Lahari Somasi ([lahari@stanford.edu](mailto:lahari@stanford.edu))
- Teo Ivancevic ([tivancev@stanford.edu](mailto:tivancev@stanford.edu))
- Muhammad Talha Salani ([salani01@stanford.edu](mailto:salani01@stanford.edu))

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/username/drug-usage-predictions.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis scripts:
   - For predictive modeling: `python predict_cannabis.py`
   - For clustering: `python clustering_analysis.py`

## License
This project is licensed under the MIT License.

## Acknowledgments
- Dataset provided by the UCI Machine Learning Repository.
- Thanks to our discussion section for support and feedback.
```

This `README.md` is concise, covers the essentials, and provides users with clear instructions to understand and replicate your work. Let me know if you’d like to include anything else!

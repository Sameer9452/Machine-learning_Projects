# Lead Conversion Prediction

## Overview
This project aims to build a predictive model to identify the most promising leads for X Education, an online education company. By assigning a lead score to each potential lead, the model helps prioritize efforts to maximize lead-to-sale conversion rates. The goal is to improve the typical conversion rate from around 30% to an estimated 80%.

## Project Structure

- **Data**: Approximately 9000 data points with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc.
- **Target Variable**: `Converted` (1 for converted leads, 0 for non-converted leads)
- **Objective**: Assign lead scores to identify 'Hot Leads' with higher conversion probabilities.


## Data Preprocessing

1. **Handling Missing Values**: Impute or drop missing values.
2. **Categorical Encoding**: Convert categorical variables to numerical using techniques like One-Hot Encoding.
3. **Remove 'Select' Values**: Treat 'Select' in categorical variables as null values and handle accordingly.
4. **Feature Scaling**: Normalize numerical features for better model performance.

## Exploratory Data Analysis (EDA)

- **Visualizations**: Histograms, box plots, and scatter plots to understand data distributions and relationships.
- **Correlation Analysis**: Identify relationships between features and the target variable.

## Model Development

1. **Feature Selection**: Select the most relevant features using techniques like correlation analysis and feature importance.
2. **Model Selection**: Train and evaluate multiple models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
3. **Hyperparameter Tuning**: Optimize model parameters using Grid Search or Random Search.

## Model Evaluation

- **Metrics**: Use accuracy, precision, recall, F1-score, and ROC-AUC to evaluate model performance.
- **Cross-Validation**: Perform cross-validation to ensure model generalizability.

## Results

- **Lead Scores**: Generate lead scores for the dataset.
- **Conversion Rate**: Target an improved conversion rate of approximately 80%.


## Future Work

- **Feature Engineering**: Explore additional features that may improve model performance.
- **Model Improvement**: Experiment with advanced algorithms and ensemble methods.
- **Real-time Data**: Integrate with real-time data sources for continuous lead scoring.

## Conclusion

This project provides a comprehensive approach to identifying potential leads for X Education, significantly improving the efficiency of their sales process by focusing on leads with a higher probability of conversion.

## Acknowledgments

- **X Education**: For providing the dataset and domain knowledge.
- **Mentors and Peers**: For guidance and feedback throughout the project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Feel free to reach out if you have any questions or need further assistance. Happy learning!

---

**Author**: Mohmed Sameer Sheikh  

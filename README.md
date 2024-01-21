# Drug-Discovery-Prediction

### Overview
This project implements predictive models, leveraging Decision Trees and Naïve Bayes, to classify compounds as active (1) or inactive (0). The training dataset consists of 800 records with an imbalanced distribution of 78 actives and 722 inactives and the test dataset consists of 350 features. The challenge is to identify features within the binary representations of compounds to develop effective binary classification models. The aim is to optimize F1 scores, given the imbalanced distribution of data.

### Implementation
🎯 Started with comprehensive dataset analysis which revealed a clean dataset. I converted the features into binary vector, each place in the vector represents if the feature is present in the compound or not.
🎯 To navigate a dataset with potentially thousands of binary features, I then employed the chi-squared test to assess the relationship between features and the target variable. Cross-validating the feature fraction, I chose to retain 90% of features to reduce dimensionality and overfitting
🎯 
🎯
🎯
🎯

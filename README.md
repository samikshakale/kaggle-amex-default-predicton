# kaggle-amex-default-predicton
Predictive model for future default based on customer's monthly profile

# Setup
Download amexfeather dataset from https://www.kaggle.com/datasets/munumbutt/amexfeather and move into a subdirectory titled amexfeather.

# Use
Run the submission notebook to generate csv file containing the default probabilities for each customer in the test set, using best model determined from EDA notebook.

# Notes
The imblearn package will not work unless you are using the 1.0.2 version of scikit-learn
The amexfeather dataset is 16GB so make sure you have enough space (might need to use kaggle environment to run the notebook)



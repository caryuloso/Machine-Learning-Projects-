# Dataset-Cleaning-Mammographic-Masses-Dataset
A python script that looks for errors in a mammogrpahic mass data set and prepares it for a random forest ML alorithm
  1. Adjusting the dataframe (adding column names, removing columns that are not needed by the model, etc.)
  2. Familiarize user with the data
     - Checks if there is missing data 
     - Checks the split of benign and malignant records on the dataset
     - Fix data types of the input data
     - Changes numerical representation of categorical data to actual catgory names
  3. Binarize the categorical input data
  4. Split the data to test and train data (test data = 20% of the records from the preprocessed dataframe) 
  5. Build a random forest classifier

# EDAStrokePrediction
Exploratory Analysis on Stroke Prediction System
# Author

Name: Jacinta Chioma Odirichukwu (PhD in Computer Science)
Phone: +2348153496082
Email: lmssmarthub@gmail.com

# 1.  Data Collection: 
Download Dataset

To use this project, you need to download the dataset from the following URL:

[**Download Dataset**](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

Please ensure that you have the necessary permissions to access and use the dataset according to its licensing terms. Once downloaded, you can place the dataset file in the appropriate directory within your project.

# 2.  Data Exploration:Explored the dataset to understand its structure, features, and distributions.
Identified potential relationships between features and the target variable (price).
### Load the dataset from where you store it and view it using the code below
![Alt text](image.png)
### Output for stroke dataset view
![Alt text](image-1.png)
### view the first five rows using this code
![Alt text](image-2.png)
### Result for view the first five rows
![Alt text](image-3.png)
### view the last five rows using this code
![Alt text](image-4.png)
### Result for view the first five rows
![Alt text](image-5.png)
### Check data types and missing values
![Alt text](image-6.png)
### Result for Checking data types 
![Alt text](image-7.png)
### Check missing values
![Alt text](image-8.png)
### Result for missing values
![Alt text](image-9.png)
### Statistical summary
![Alt text](image-10.png)
### Output Statistical summary
![Alt text](image-11.png)
### Check for duplicates
![Alt text](image-12.png)

### Output Check for duplicates
![Alt text](image-13.png)
### Handling missing values using fill forward (ffill)
![Alt text](image-14.png)
### Output Handling missing values, you can see that missing bmi at row 1 has been filled
### Notice that NaN has been filled with 36.6, that is the function of ffill method
![Alt text](image-15.png)
### Encode categorical variables
![Alt text](image-16.png)
![Alt text](image-17.png)
### Output for Encode categorical variables
![Alt text](image-18.png)
![Alt text](image-19.png)
![Alt text](image-20.png)

# Check for missing values to see if it is filled
missing_values = data.isnull().sum()
print("Missing Values:\n", missing_values)
### Output showing that, there are no more missing data
![Alt text](image-21.png)
### Code to Extract numerical columns
![Alt text](image-23.png)
![Alt text](image-24.png)
### Output for the numerical column
![Alt text](image-25.png)
### Drop the id column
![Alt text](image-26.png)
### Convert all datatype to integer
![Alt text](image-27.png)
### Output for dataset in numerical form
![Alt text](image-28.png)

### Save the cleansed data as new dataset and save it in your local machine.
![Alt text](image-30.png)

# Conclusion
The dataset was cleaned and normalized as part of an exploratory data analysis before being utilized to train the model.

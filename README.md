# deep-learning-challenge
Submitted by Kaylyn Valdez-Scott Date: 25-JAN-2024 Project Title: Module 21 Alphabet Soup Challenge 

**Purpose of project** : using knowledge of machine learning and neural networks, examine the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup foundation.

Assignment is broken down into 5 sections:

1. Preprocess the Data
2. Compile, Train, and Evaluate the Model
3. Optimize the Model
4. Write a Report on the Neural Network Model
5. Copy Files Into Your Repository

**Results**

**Data Processing** 

Using target variables such as 'IS_SUCCESSFUL' column from application_df, I split the data into training and testing datasets. 
Features of my model include columns "APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AMT,	IS_SUCCESSFUL". This was determined after cleaning the dataset and dropping the columns "EIN" and "NAME".

**Compiling, Training, and Evaluating the Model**

In my first attempt on the starter code sheet, i used 10 hidden_nodes_layer1 and 5 hidden_nodes_layer2. These were selected in order to start smaller on the first try, and build upon them using higher numbers for attempt two and three. In all three attempts, I was not able to achieve the 75% model accuracy target. In order to get closer to the 75%, I added more layers, removed more columns, and added additional hidden nodes. Still, I was only able to reach approximately 73%. 

The below photos show work from Attempt One, Two and Three with accuracy results. 

<img width="1353" alt="Screenshot 2024-01-25 at 1 01 58 PM" src="https://github.com/kaylynvaldezscott/deep-learning-challenge/assets/141589524/a286ad31-57fc-4028-82fd-f766bf15bcbc">

<img width="1345" alt="Screenshot 2024-01-25 at 1 02 29 PM" src="https://github.com/kaylynvaldezscott/deep-learning-challenge/assets/141589524/633ebb0a-7540-4d7b-921d-44af943d2e89">

<img width="1355" alt="Screenshot 2024-01-25 at 1 03 15 PM" src="https://github.com/kaylynvaldezscott/deep-learning-challenge/assets/141589524/de2d81e2-cfd5-4ff6-aa57-cf55f8264837">

<img width="1350" alt="Screenshot 2024-01-25 at 1 03 38 PM" src="https://github.com/kaylynvaldezscott/deep-learning-challenge/assets/141589524/2945cca9-2fec-4cbb-9acd-90f6c71b2a1d">

<img width="1345" alt="Screenshot 2024-01-25 at 1 04 11 PM" src="https://github.com/kaylynvaldezscott/deep-learning-challenge/assets/141589524/6245920b-fa16-4511-a537-ea59cc41dca6">



**Summary**

In conclusion, the deep learning model was around 73% accurate in predicting whether or not the applicants will be successful if funded. Using a model with greater correlation between input and output would likely result in higher prediction accuracy, as well as potentially eliminating more columns that do not contribute. The data should be cleaned more thoroughly upfront before making more attempts, as well as trying different activations for the hidden layers. 

# 102103043_Topsis_PretrainedModel
This is an Assignment Task for finding the best pre-trained model taken from Hugging Face for comparing the best model for text sentence similarity.

# Title
Topsis to find the best pre-trained Model for text sentence similarity.

# Methodology 
![image](https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/4bdd0de2-dad8-45a0-b53e-9059d5bd8133)

In the First stage, lines of sentences were collected based on different evaluation parameters to be tested on. The sentences were tokenized , models were extracted from Hugging Face, models were used to find sentecne similarity between the tet pairs based on 4 evaluation parameters and results were stored in a CSV File.

# Description :
1. Text Similarity Analysis:
Input Data: We started with the input data, which included text pairs and their similarity scores for different models.

2. Analysis:
We performed analysis based on four evaluation parameters: Short vs. Long Sentences, Simple vs. Complex Syntax, Semantically Similar vs. Dissimilar Pairs, and Paraphrase vs. Non-Paraphrase.
CSV File Creation:

3. Python Code:
 We created a Python script to organize the data into a CSV file with columns for text, models, and the four evaluation parameters.

4. Topsis Analysis:

Normalization: We normalized the data to prepare it for TOPSIS analysis.
Weights and Impact: We assigned weights (1, 1, 2, 2) and impact signs (-, -, +, +) to the parameters for TOPSIS based on the specific I am performing for sentence similarity.
Python Code: We wrote Python code to apply TOPSIS analysis on the normalized data.

# Input/Output :

The CSV File for Input and Output has been uplooad in the repository section namely 'performance_values.csv' and 'results_model_scores_topsis'.

# Results :

 I found that 'distilbert-base-uncased' model showed the best outcomes for sentence similarity with a Topsis Rank of 1 and score 0.498832935937369.

 <img width="914" alt="image" src="https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/347f126d-961f-4ddf-a284-02f7c1d48f2c">

# Graphical Analysis :
Following is the Graphical Analysis for the same :

![image](https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/4c92ac8d-f8ae-450d-9486-a5b2ca045fb8)





 


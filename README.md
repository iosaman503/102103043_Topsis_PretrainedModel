# 102103043_Topsis_PretrainedModelsComparison
This Project aims to find the best pre-trained model taken from Hugging Face for comparing the best model for text sentence similarity.

# Title
To find the best pre-trained Model by applying Topsis for text sentence similarity.

# Methodology 
![image](https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/4bdd0de2-dad8-45a0-b53e-9059d5bd8133)

In the initial phase, sentence data was gathered, comprising various sentence pairs intended for evaluation based on distinct parameters. Subsequently, tokenization was applied, and models were retrieved from Hugging Face. These models were then employed to compute sentence similarity for the given text pairs across four evaluation parameters. The outcomes were recorded and stored in a CSV file for further analysis.

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
Weights and Impact: We assigned weights (1, 1, 2, 2) and impact signs (-, -, +, +) to the parameters for TOPSIS based on the specific task that I am performing of sentence similarity.
Python Code: We wrote Python code to apply TOPSIS analysis on the normalized data.

# Input/Output :

The CSV File for Input and Output has been uplooad in the repository section namely 'text_model_scores.csv' and 'results_model_scores_topsis'.

# Results :

 I found that 'distilbert-base-uncased' model showed the best outcomes for sentence similarity with a Topsis Rank of 1 and score 0.498832935937369.

 <img width="914" alt="image" src="https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/347f126d-961f-4ddf-a284-02f7c1d48f2c">

# Graphical Analysis :
Following is the Graphical Analysis for the same :

![image](https://github.com/iosaman503/102103043_Topsis_PretrainedModel/assets/90442567/abd6b433-cca2-4a78-90f6-c91505568197)






 


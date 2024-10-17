# Finding_Dory_Classification

Using the script of *Finding Dory*, this project compares four supervised ensemble classification methods (namely Bagging, Random Forest, Gradient Boosting, ADA Boosting, and XG Boosting) on their ability to accurately predict which of the top ten main characters said which line.

The stimuli used in this analysis are lines of dialogue from the script of *Finding Dory* obtained from [Kaggle](https://www.kaggle.com/datasets/ashtrindade/finding-dory-movie-script). For simplicity of the current task, the script is filtered to only include the top ten characters that have the most lines, then tokenized using `nltk`. 

The analysis aims to compare the ability to accurately classify each line to the correct character across various supervised ensemble machine learning methods. Different manipulations of model are also examined, such as comparing models trained on unigrams vs. bigrams vs. trigrams and removing stopwords.

Despite the simplicity of the classification task, this report aims to highlight the challenges associated in naive textual analysis, and emphasizes the need for more sophisticated methods in text/linguistic classification tasks.

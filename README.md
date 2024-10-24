# Predicting *Finding Dory* characters from film dialogue using supervised ensemble classification methods

Using the script of Finding Dory, can machine learning ensemble classification methods (Bagging, Random Forest, Gradient Boosting, ADA Boosting, and XG Boosting) accurately predict what character said which line?

In this project, I aim to examine how well ensemble classification methods perform on tasks that rely solely on text as data. Here, lines of the Finding Dory script are vectorized and treated as independent variables in the models, then used predict the dependent variable: the corresponding character that delivered that line.

## Python Packages Used

- **Data Manipulation:** `numpy`, `string`, `nltk`, `pandas`, `sklearn`, `xgboost`
- **Data Visualization:** `matplotlib.pyplot`

## Data
The stimuli used in this analysis are lines of dialogue from the script of Finding Dory obtained from [Kaggle](https://www.kaggle.com/datasets/ashtrindade/finding-dory-movie-script). The dataset contains two variables:

  - name (str): The name of the character associated with the line.

  - line (str): The dialogue delivered by that character.

## Results and Evaluation

Overall, models perform poorly on accurately classifying the text to the corresponding character that delivered each line. This highlights the challenges associated with naive textual analysis, and emphasize the need for more sophisticated methods in text/linguistic classification tasks.

## License

[MIT License](https://opensource.org/license/mit/)

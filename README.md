# Game of Thrones Character Analysis: Appearances and Survival

<p align="center">
  <img src="![image](https://github.com/1AyaNabil1/Game_of_Thrones_Character_Analysis/assets/96292588/0c2412c4-2d5c-49da-b7c8-3ea009519f7d)
" alt="Game of Thrones GIF"/>
</p>

## Project Overview

This project provides an in-depth analysis of characters from the "Game of Thrones" series, focusing on the factors that influence their appearances throughout the books and their likelihood of survival. Using a dataset that encapsulates various character attributes, the analysis explores the statistical relationships between these attributes and character outcomes, including the use of logistic regression and Random Forest to predict survival.

## Key Objectives

- To understand the correlation between different numerical features of the characters.
- To build predictive models that estimate the total number of character appearances based on attributes such as nobility and gender.
- To predict character survival using logistic regression and Random Forest, assessing feature importance and model performance.
- To conduct hypothesis testing to statistically examine the differences in appearances between noble characters and commoners.

## Methodology

- **Correlation Analysis**: A heatmap visualization of the correlation matrix to identify potential relationships between variables.
- **Linear Regression**: Separate models to predict total appearances based on nobility and gender.
- **Logistic Regression**: A model to predict the binary outcome of character survival, using 'Death Year' as the target variable and features including 'Gender', 'Nobility', and appearances in each book.
- **Random Forest Classification**: A model to predict the survival status of characters, with an analysis of feature importance.
- **Hypothesis Testing**: An independent t-test to compare the total appearances of nobles versus commoners.

## Results

The analysis revealed that nobility status is a significant predictor of a character's total appearances, with noble characters appearing more frequently than commoners. The logistic regression and Random Forest models provided insights into the factors that contribute to a character's survival, with certain features being particularly influential.

## Visualizations

The project includes histograms and bar plots to visualize the distribution of appearances and the coefficients of the predictive models, respectively. These visualizations complement the statistical findings and provide an intuitive understanding of the data.

## Conclusions

The project concludes that nobility status, gender, and appearances in specific books are key factors influencing a character's prominence and survival in the "Game of Thrones" series. The statistical tests and predictive models offer quantitative evidence for these insights, making this analysis a valuable resource for fans and data enthusiasts alike.

## How to Use This Repository

- `Game_of_Thrones(Character Deaths).ipynb`: The Jupyter notebook containing all the analysis code, visualizations, and comments.
- `data/`: The directory containing the dataset used for the analysis.
- `requirements.txt`: A list of Python packages required to run the notebook. The contents of the file are as follows:
To replicate the analysis, clone the repository, install the required packages using `pip install -r requirements.txt`, and run the Jupyter notebook.

## License

This project is open-sourced under the MIT license. Feel free to fork the repository, contribute, or use the analysis in your own projects. Please provide proper attribution if you do.

## Acknowledgments

Thanks to the creators of the "Game of Thrones" series for inspiring this analysis, and to the data science community for providing the tools and techniques used in this project.

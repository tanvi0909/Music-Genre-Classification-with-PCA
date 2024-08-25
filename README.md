# 🎵 Music Genre Classification Project with PCA and Logistic Regression
A Machine Learning Project Predicting Music Styles through Dimensionality Reduction

![Music Genre](guitar.jpg)

## Project Overview
In the era of digital streaming, categorizing and recommending music based on genres is essential. This project aims to classify music genres using a dataset of musical features extracted from tracks across various styles. Despite some missing genre labels, the objective is to predict the genres of these unlabeled tracks.

To achieve this, we employ Principal Component Analysis (PCA) for dimensionality reduction, simplifying the dataset while uncovering hidden patterns. The transformed principal components are then used to train a logistic regression model to classify the music genres effectively.

### Key Objectives:

- Perform data exploration and understand the feature set.
- Conduct correlation analysis to identify relationships between features.
- Apply PCA to reduce dimensionality and retain significant variance.
- Evaluate classification performance using logistic regression on both original and PCA-transformed data.
- Develop a system for genre prediction and integration.

## Project files
The music data for the Music Genre Classification project can be found in the music_dataset_mod.csv file, and the data legend is provided in the Music Data Legend.xlsx. To get started, you can download the Music Genre Classification with PCA - Project.ipynb notebook, open it in Jupyter Notebook, and run the first cell to import the required libraries.

## Data Exploration

- Performed initial data analysis to understand the distribution of each feature.
- Visualized data using histograms, box plots, and scatter plots to gain insights into feature distributions and relationships.
- Checked for missing values and handled them appropriately.

## Correlation Analysis

- Conducted correlation analysis to understand relationships between different audio features.
- Visualized the correlation matrix to identify highly correlated features, which could be candidates for dimensionality reduction.

## Dimensionality Reduction with PCA

- Applied PCA to the dataset to reduce the number of features while retaining significant variance.
- Explained the variance captured by each principal component and selected an optimal number of components for classification.
- Visualized the transformed feature space to understand how PCA compresses information.

## Model Building

### 1. **Logistic Regression on Original Data**:
   - Built a logistic regression model using the original set of features.
   - Evaluated the model’s performance using accuracy, precision, recall, and F1 score.

### 2. **Logistic Regression on PCA-Transformed Data**:
   - Built a logistic regression model using the PCA-transformed features.
   - Compared the performance of this model with the one trained on the original features.

## Evaluation and Results

- Compared the classification efficacy of the models using original and PCA-transformed data.
- Highlighted the trade-offs between dimensionality reduction and classification accuracy.
- Visualized the results using confusion matrices, ROC curves, and precision-recall plots.

## Genre Prediction and Integration

- Prepare the data to predict music genres of unlabeled tracks using the trained logistic regression model.
- Display the dataframe with predicted genres.

## Conclusion

- Discussed the findings and insights gained from the project.
- Highlighted the benefits and limitations of using PCA for dimensionality reduction in music genre classification.
- Summarized the overall performance of the classification models and their implications.

## Future Work

- Explore the use of other dimensionality reduction techniques such as t-SNE or autoencoders.
- Experiment with different classification algorithms like SVM, Random Forest, or Neural Networks.
- Expand the dataset to include a broader variety of music genres and audio features.
- Develop a more robust interface for real-time genre prediction.

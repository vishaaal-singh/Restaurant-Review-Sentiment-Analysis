# Restaurant Review Sentiment Analysis with Naive Bayes

This project demonstrates sentiment analysis of restaurant reviews using a Naive Bayes classifier. The model is trained on a dataset of restaurant reviews and can predict whether a review is positive or negative.

## Dataset

The dataset used in this project is a TSV file named `Restaurant_Reviews.tsv`. It contains 1000 restaurant reviews labeled as positive or negative.

## Methodology

The following steps are performed in this project:

1. **Data Cleaning:**
   - Removing special characters and converting text to lowercase.
   - Removing stop words (except "not").
   - Applying stemming to reduce words to their root form.

2. **Bag of Words Model:**
   - Creating a Bag of Words model using `CountVectorizer` with a maximum of 1500 features.

3. **Model Training:**
   - Splitting the dataset into training and testing sets.
   - Training a Gaussian Naive Bayes classifier on the training set.

4. **Model Evaluation:**
   - Predicting the sentiment of reviews in the test set.
   - Evaluating the model's performance using a confusion matrix and accuracy score.

## Libraries Used

- NumPy
- Matplotlib
- Pandas
- NLTK
- Scikit-learn

## Usage

1. Upload the `Restaurant_Reviews.tsv` file to your Google Colab environment.
2. Copy and paste the code into a Colab notebook.
3. Run the code cells to perform sentiment analysis on the dataset.

## Results

The accuracy of the Naive Bayes model on the test set is printed in the output. The confusion matrix shows the number of true positives, true negatives, false positives, and false negatives.

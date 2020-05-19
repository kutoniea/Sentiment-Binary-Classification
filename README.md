The data of this sentiment analysis is IMDb reviews with training, development, and testing datasets.
The analysis is binary classification (good or bad review).
The model is supervised learning.

To run the code,
First, download the data (IMDb.zip) in this repository.
Second, follow the code instruction in ipython file.
 1. Read the data.
 2. Data preprocessing with removing stopwords, tokenisating words, lemmatising words, and lowercasing words.
 3. Encode data result.
 4. Define features of the model: four features were chosen here.
    - Word Frequency - Top 5000 Frequent Adjective and Verb Words.
    - No. of Postive and Negative Words from Opinion Lexicon.
    - tf-idf with 1000 Features.
    - Similarity Score between 'Good', 'Bad' and Adjective Word.
 5. Feature selection: utlise KBest to conduct feature selection (assing number of features that will be leaved in the final model).
 6. Train the model: naive, SVM, and logistic regression.
 7. Validate all steps with development datasets.
 8. Test the model with testing datasets.

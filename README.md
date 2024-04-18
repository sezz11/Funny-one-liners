#Binary classification of funny one-liners

This project contains a Jupyter Notebook that demonstrates how to scrape, preprocess, and analyze text data to detect humor. The main objectives are to scrape one-liners from an online joke repository, preprocess this textual data, and use machine learning models to classify text as humorous or non-humorous.

## Repository Contents

- `humorous_jokes.txt`: A text file containing jokes scraped from [onelinefun.com](https://onelinefun.com/).
- `code.ipynb`: The Jupyter Notebook containing all the code for scraping, preprocessing, sentiment analysis, and machine learning classification.
- `english_proverbs.txt`, `reuters_headlines.txt`: Non-humorous text datasets for the analysis.
- `preprocessed_humorous_texts_with_labels.pickle`: Serialized Python object with preprocessed humorous text and sarcasm labels.
- `combined_non_humorous_texts.pickle`: Serialized Python object with combined non-humorous texts.
- `data/`: Directory containing any data files used by the notebook.

## How to Use

1. **Setup Your Environment**: Make sure you have Python installed, along with the libraries `requests`, `BeautifulSoup`, `nltk`, `textblob`, and `pickle`.

2. **Install Dependencies**: Run `pip install -r requirements.txt` to install the necessary packages.

3. **Run the Notebook**: Open `code.ipynb` in Jupyter Lab or Jupyter Notebook and execute the cells in sequence.

## Project Structure

The notebook is structured as follows:

1. **Scraping**: Collecting jokes from [onelinefun.com](https://onelinefun.com/).
2. **Preprocessing**: Tokenization, stop words removal, lemmatization, and other text normalization techniques.
3. **Sentiment Analysis**: Using `TextBlob` to detect sarcasm within the jokes.
4. **Data Serialization**: Storing and loading preprocessed text data using `pickle`.
5. **Machine Learning**: Training Naive Bayes, SVM, and LSTM models to classify text.
6. **Evaluation**: Comparing the performance of the models using accuracy, precision, recall, and F1-score.

## Visualization

The project includes data visualization techniques like word frequency bar charts, word clouds, and ROC curves for model evaluation.



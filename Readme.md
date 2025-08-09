# Binary Text Classification: IMDB Movie Review Sentiment Analysis

This project demonstrates binary text classification using IMDB movie reviews. The goal is to classify reviews as either **positive** or **negative** using machine learning techniques.

## Project Structure

- `Binary Text Classification.ipynb`: Main Jupyter notebook containing all code and analysis.
- `IMDB Dataset.csv`: Dataset of IMDB movie reviews and their sentiment labels.
- `dataset.zip`: Compressed version of the dataset.
- `M508 Assessment Brief.pdf`: Project brief and requirements.
- `M508B Big Data Analytics - GH104311 - Movie Review.html`: Exported HTML version of the notebook.

## Workflow

1. **Data Loading**: Reads the IMDB dataset into a pandas DataFrame.
2. **Text Preprocessing**: Cleans and normalizes text (removes HTML tags, punctuation, stopwords, and applies lemmatization).
3. **Feature Engineering**: Converts text to numerical features using TF-IDF vectorization.
4. **Model Training**: Trains machine learning models (Logistic Regression, Multinomial Naive Bayes) on the processed data.
5. **Evaluation**: Evaluates model performance on a test set.
6. **Visualization**: Includes word clouds and distribution plots for exploratory data analysis.

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- scikit-learn
- nltk
- matplotlib
- wordcloud

## Usage

1. Place `IMDB Dataset.csv` in the project folder.
2. Open `Binary Text Classification.ipynb` in Jupyter Notebook.
3. Run all cells to execute the workflow.

## Notes

- NLTK resources (`stopwords`, `wordnet`, `omw-1.4`) are downloaded automatically in the notebook.
- The notebook is self-contained and includes error handling for missing files.

## License

This project is for educational purpose.

# Arabic Text Data Cleaning and Preprocessing

This repository contains a Jupyter notebook for cleaning and preprocessing Arabic text data using Python and various NLP libraries.

## Features:

- **Data Cleaning**: Removal of unnecessary columns, duplicates, and null values.
- **Text Preprocessing**: Removing mentions, links, retweets, punctuations, English text, duplicated characters, unwanted words, and emojis.
- **Normalization**: Normalizing Arabic text by removing diacritics and standardizing letters.
- **Tokenization**: Splitting text into tokens.
- **Stopword Removal**: Removing Arabic stopwords.
- **Lemmatization**: Converting words to their base form.
- **Stemming**: Reducing words to their root form.
- **Data Saving**: Saving the cleaned data to a CSV file.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - nltk
  - re
  - string
  - qalsadi
  - pyarabic
  - camel-tools

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```

2. **Navigate to the Directory**

   ```bash
   cd your_repository
   ```

3. **Install Required Libraries**

   ```bash
   pip install pandas numpy nltk qalsadi pyarabic camel-tools
   ```

4. **Download NLTK Data**

   Open a Python shell or include the following in your script:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

## Usage

1. **Place Your Dataset**

   Ensure your dataset (`كأس_العالم#.csv`) is placed in the same directory as the notebook.

2. **Run the Notebook**

   Open `arabic_text_preprocessing.ipynb` in Jupyter Notebook and run the cells step by step.

3. **Output**

   The cleaned data will be saved as `clean_data.csv` in the same directory.

## Notes

- Make sure all the necessary libraries are installed.
- Adjust the dataset path if it's located elsewhere.
- The morphology database for `camel-tools` should be correctly installed if you're using advanced morphological analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

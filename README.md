# The Shawshank Redemption NLP Analysis

This project conducts natural language processing (NLP) analysis on the script of "The Shawshank Redemption". The analysis includes text extraction from a PDF, text cleaning, named entity recognition (NER), sentiment analysis, and network visualization of character interactions.

## Project Description

This project comprises Python scripts utilizing various NLP libraries and techniques to analyze the script of "The Shawshank Redemption". Below is a brief overview of the functionalities:

- **Text Extraction**: The script is extracted from a PDF file using PyPDF2 and Textract libraries.
- **Text Cleaning**: The extracted text is cleaned by removing punctuation, stopwords, and lemmatizing words using NLTK.
- **Named Entity Recognition (NER)**: Potential names are identified using regular expressions and NLTK.
- **Sentiment Analysis**: Sentiment analysis is performed using TextBlob and VADER Sentiment Analysis tools.
- **Word Cloud Generation**: A word cloud of the most common words is generated using the WordCloud library.
- **Summarization**: Text summarization is implemented using the Hugging Face transformers library.
- **Character Interaction Network Visualization**: The interactions between characters are visualized using NetworkX and Matplotlib.

## Dataset Source

    ```
    https://www.kaggle.com/datasets/swarajkhan/shawshank-redemption-script-for-nlp
    ```

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/swaraj-khan/shawshank-nlp-analysis.git
    ```

## Usage

1. Ensure you have the PDF file containing the script named `ssr.pdf` in the project directory.
2. Take a look at the Jupyter notebook `app.ipynb` to understand the NLP analysis:
3. The notebook will help you understand various analyses and generate visualizations in the project directory.

## Results

- The cleaned text is saved as `clean_data.txt`.
- A word cloud image (`Manifesto_top_100.jpeg`) of the top 100 most common words is generated.
- Sentiment analysis results are printed to the console.
- A network graph of character interactions is displayed using Matplotlib.

## Acknowledgements

- The script extraction and text cleaning processes are inspired by various NLP tutorials and documentation.
- The named entity recognition and sentiment analysis implementations utilize NLTK and TextBlob libraries.
- Character interaction network visualization is achieved using NetworkX and Matplotlib.

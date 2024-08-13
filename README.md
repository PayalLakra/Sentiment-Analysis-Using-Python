Amazon Review Sentiment Analysis:: This project provides a GUI application to analyze the sentiment of Amazon reviews using Natural Language Processing (NLP) techniques. The application allows users to input reviews directly or fetch reviews from an Amazon product page and visualize the sentiment distribution.

## Features

- **Input Reviews Directly**: Users can type or paste Amazon reviews into the application.
- **Fetch Reviews from Amazon**: Automatically fetch reviews from an Amazon product page URL.
- **Visualize Sentiment Distribution**: Display a visual representation of the sentiment distribution of the reviews.

## Libraries Used

- **pandas**: For data manipulation and analysis. Used to load and preprocess the dataset containing Amazon reviews.
- **scikit-learn**: Provides tools for data mining and analysis. Includes `TfidfVectorizer` for converting text data into numerical features.
- **nltk**: The Natural Language Toolkit for natural language processing. Uses `SentimentIntensityAnalyzer` from the VADER module for sentiment analysis.
- **matplotlib**: For creating visualizations. Plots the sentiment distribution of reviews.
- **requests**: For sending HTTP requests to fetch reviews from Amazon product pages.
- **beautifulsoup4**: Parses HTML and XML documents to extract review text from Amazon product pages.
- **tqdm**: Provides a progress bar to indicate the status of fetching reviews.
- **tkinter**: Standard Python interface for creating the graphical user interface (GUI) of the application.

## Screenshots

![Screenshot (188)](https://github.com/PayalLakra/Sentiment-Analysis-Using-Python/assets/134941931/e674c402-7fb8-4fe9-a15d-283ee100a783)
![Screenshot (190)](https://github.com/PayalLakra/Sentiment-Analysis-Using-Python/assets/134941931/1bee4382-6627-4643-ab6e-e4ff35f4e6b9)
![Screenshot (220)](https://github.com/PayalLakra/Sentiment-Analysis-Using-Python/assets/134941931/32910dd1-4098-4719-a544-539d08f50a27)
![Screenshot (221)](https://github.com/PayalLakra/Sentiment-Analysis-Using-Python/assets/134941931/a730a46f-1949-48bf-88f8-1d35d6b3cdeb)
![Screenshot (222)](https://github.com/PayalLakra/Sentiment-Analysis-Using-Python/assets/134941931/d7acf9d3-ed3e-4c88-8289-1d26b4331f2a)

## Requirements

- Python 3.x
- Required Python libraries listed in `requirements.txt`

## Installation

1. **Clone the Repository**

   ```bash
   https://github.com/PayalLakra/Sentiment-Analysis-Using-Python.git
   cd Sentiment-Analysis-Using-Python
   ```

2. **Install the Required Python Packages**

   ```bash
   pip install -r requirements.txt
   ```

   Ensure that you have the following libraries installed: `pandas`, `scikit-learn`, `nltk`, `matplotlib`, `requests`, `beautifulsoup4`, `tqdm`, `tkinter`.

## Usage

1. **Run the Application**

   Execute the following command to start the application:

   ```bash
   python CodeSentimentAnalysis.py
   ```

2. **Using the Application**

   - **Input Reviews Directly**: Type or paste the review text into the input area and click the analyze button.
   - **Fetch Reviews from Amazon**: Enter an Amazon product page URL and click the fetch button to retrieve and analyze reviews.
   - **View Results**: The sentiment distribution of the reviews will be displayed visually.



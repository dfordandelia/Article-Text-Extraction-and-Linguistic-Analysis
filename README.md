# Article-Text-Extraction-and-Linguistic-Analysis

Description:
This Python script performs two main functions: extracting text from URLs specified in an Excel file and conducting linguistic analysis on the extracted text. 

The first part of the script utilizes the `pandas` library to read an Excel file containing URLs. It then iterates over each row in the dataframe, extracts the article text from the corresponding URL using web scraping techniques with `requests` and `BeautifulSoup`, and saves the extracted text to individual text files.

The second part focuses on linguistic analysis. It utilizes `nltk` for natural language processing tasks such as tokenization, stop-word removal, and sentence segmentation. Additionally, the script computes various linguistic variables including word count, polarity score, subjectivity score, average sentence length, percentage of complex words, Fog index, average word length, and average number of words per sentence.

To perform this analysis, the script assumes the availability of additional resources such as lists of positive and negative words, complex words, and personal pronouns. These resources are expected to be incorporated into the script for accurate linguistic analysis.

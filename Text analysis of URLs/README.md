
# Text Analysis of URLs

This is a simple project where we extract the content of URLs. The URLs I have used for this project are basically article pages. I extracted the article content in these URLs and performed some analysis which lead me to the following metrics:

- Positive score - The number of positive words in the article
- Negative score - The number of negative words in the article
- Polarity score - The score determines if the article is postive or negative in nature. Ranges from -1 to +1
- Subjectivity score - The score determines if the article is objective or subjective. Ranges from 0 to +1
- Avg sentence length - The average length of sentences in the article
- Percentage of complex words - The total percentage of complex words in the article
- Fog index - It is the index that tells the article readbaility
- Complex word count - Total number of complex words in the article
- Word count - Total number of words in the article
- Syllable per word - The number of syllables present per word
- Personal pronouns - Number of personal pronouns present in the article
- Average word length - The average word length pf the article

# Python Libraries 

- pandas - for reading the excel file containing the URLs as a dataframe to work on it.
- numpy - for performing efficient operations on the dataframe
- BeautifulSoup - for web scraping i.e extracting the article from the URLs
- nltk -  for tokenizing the article to perform our operations and analysis

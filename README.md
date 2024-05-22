# Webpage-Comparison
## Description: Comparing website similarity via Google Word2Vec Pre-trained Model
## 1. Google Word2Vec Pre-trained Model
Google Word2Vec Pre-trained Model includes word vectors for a vocabulary of 3 million words and phrases collected from Google News.
## 2. Model Access
The program will automatically detect the model in your local folder.  If it is not there, it will first download the model from the Internet. When unzipped, it is approximately 3GB.  Please ensure that your system has enough storage. 
## 3. Program Running
The model can run in two modes.  If the user has not downloaded the model previously, the program will download it first and then report an Error. The user needs to run the program for the second time to compare the website similarity.
## 4. Program Instruction
The model first downloads all HTML and CSS information from the destinated website and then transforms them into pure text content.  After that, the program will utilize the Google Word2Vec Model to translate text contents into vectorized numerical values.  Finally, the program will compare the similarity via cosine similarity.  Cosine similarity measures the size of the angle between two vectors, and the closer the value is to 1, the more similar the two vectors are.
## 5. Other Potential Solutions
There are various methods to compare the similarity of web pages, including but not limited to:
### 5.1. Text Content Similarity Comparison
By comparing the text content of web pages, such as titles, descriptions, and body text, algorithms like cosine similarity (this program), Jaccard similarity, or edit distance can be used to calculate the degree of similarity between texts.
### 5.2. Keyword Similarity Analysis
Keywords on a web page are important indicators of its theme. Techniques like Term Frequency-Inverse Document Frequency (TF-IDF) and word embeddings can be utilized to analyze keyword similarity and judge the similarity of web pages.
### 5.3. Structural Feature Similarity Assessment
Besides text and keywords, structural features of web pages (e.g., URL structure, header tags, anchor texts) are also crucial for similarity determination. Metrics like Hamming distance or Longest Common Subsequence can be used to measure the similarity of structural features.
### 5.4. User Behavior Data Similarity Consideration
User behavior data, such as click-through rates, browsing duration, and bounce rates, can serve as a reference for judging web page similarity. Methods like the Pearson correlation coefficient or Spearman's rank correlation coefficient can analyze the similarity of user behavior data.
### 5.5. Information Fingerprinting-Based Similarity Detection:
Information fingerprinting extracts key information from web pages (such as keywords, terms, sentences, or paragraphs and their weights in the pages) to generate a unique information fingerprint. If two web pages share the same information fingerprint, they are considered similar. Specific algorithms like the "shingling" algorithm involve slicing the document into overlapping sequences of words (shingles) and comparing these shingles to determine similarity.

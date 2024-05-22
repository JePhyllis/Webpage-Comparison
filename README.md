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
 

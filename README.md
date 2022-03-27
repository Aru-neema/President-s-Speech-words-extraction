# President's Speech words extraction

## Objective Statement:
In this project i am trying extract most coomon words used and clean the text for punctation and case letters for easier analysis. The dataset is uploaded from 'nltk' library from the corpus name of 'inauguural'. Then i uploaded the speeches of three presidents, Roosevelt, Kennedy and Nixon. 

Following questions were answered through this project: 
1. Find the number of characters, words and sentences for the mentioned documents.
2. Remove all the stopwords from the three speeches. Show the word count before and after the removal of stopwords. Show a sample sentence after the removal of stopwords.
3. Which word occurs the most number of times in inaugural address for each president? Mention the top three words. (after removing the stopwords)
4. Plot the word cloud of each of the three speeches. (after removing the stopwords)


## Case Steps
1. First downloaded and uploaded the required libraries for performing natural language processing 
2. Uploaded the speeches and counted the length of of characters, words and sentences
3. Converted the speech text into dataframe as it helps in easier implemntation of nltk codes
4. Replaced any unusual symbols in the speech using df.str.replace()
5. Performed stemming to bring all the words to its root word. This will help to not to recoganise same words as different
6. To find the most common words, creatd a series of words by splitting each word of the sentence with a space. Then cleaned this series of words for 'stopwords' and convered all upper case to lower case letters. Then extrated the 2000 most common words. 
7. After finding the most common words, removed the meaningless words by again running the 'stopword' function, including the meaningless word in the list of stopwords. 
8. Repeated the same for all three president
9. For wordcloud, i firstly installed and imported the wordcloud library and then constructed wordcloud after cleaning the text for stop words. 

## Result
Finding out the top three words and wordcloud helped in understanding the general and individual theme of the speech of the president's. This helps us to know what message each president wanted to focus on, in their speeches. 


## Data preparation
Code Used: Python

Python Version: 3.8.8

Packages: nltk, inagural, re, string, pandas

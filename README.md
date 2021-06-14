# Introduction
## Question
How have the lyrics of the most popular songs in the US changed over time?
## Why Does It Matter?
Music tends to reflect the current state of society. As our society has gotten more progressive and open, so have our popular music lyrics. By looking at how lyrics have changed since 1950, an arugment can be made regarding what is considered acceptable in the United States. For example, if technology is mentioned more often, it could be reflecting the rise of technology in our society. Additionally, an increase in lyrics about provactive actions can indicate that our society has relaxed our standards around sex. By analyzing different themes in in popular music lyrcis, commentary on the values of our society can argued.
# Sources
I am using a csv file created by Eunice Chan (https://github.com/eunice-chan/DH_PROJ_Billboard) that details the Billboard Top 100 from 1950-2018. Additionally, much of the intial data cleaning, formatting, and basic analysis is taken from Chan's project. Chan manually inputted lyrics, but I am hoping to webscrape so that I can have a larger library of words.  

I will be using Rishabh Parekh's project(https://github.com/rishabh-parekh/dh100final) as a guideline on how to webscrape from genius.com. While Parekh only found the lyrics for four songs using this technique, I am hoping to adapt it to be able to webscrape lyrics for all the Billboard Top 100 Songs 1950-2018. 

Furthermore, I have found inspiration for this project from a Medium article (https://medium.com/the-omnivore/the-evolution-of-the-american-pop-lyric-61ef31b24f03) that studied a similar question. I will be expanding on this by including more association words and looking at more themes. 

# Workflow
1. Upload 'Billboard100(1950-2018).csv'created by Eunice Chan to Jupyter Notebook.
2. Drop the manually added lyrics column and webscrape for all lyrics using technique by Rishabh Parekh.
3. Perform basic data analysis with influence from Chan's work in Jupyter Notebook.
## CTA Analysis:

1. Preprocessing Lyrics without punctuation, lyrics by phrases, lyrics by words.
2. Basic: Unique artists in decade, unique artists, number of times artists appear, unique phrases, average character count, average word count.
3. Frequency: Parts of speech distribution (by decade), sepculative words, personal pronouns (total, first vs second, first person singular vs first person plural, genders), lexical diversity.
4. Research Question Analysis: Analysis the frequency of words associated with chosen themes. 
5. Network graph
6. Sentiment analysis (by phrases)
7. Common words: direct count (without stopwords), TF-IDF, topic modeling

# Assumptions & Concerns
I am currently strugging to webscrape lyrics for all of the songs. It seems to be mainly a debugging issue that I should be able to get resolved. Once I fix that, I will need to ensure that the webscraping worked for all of the songs. In the case that not all lyrics could not be webscraped, I will need to ensure that every year (or decade) has the same number of songs to ensure that there is not unexpected bias. Furthermore, it will be difficult to idenitfy every association word for a theme. It is possible that a word could be referencing another theme or that it could be completeley unrelated in certain cases. 
    
# Tools & Methods
## Preliminary Importing

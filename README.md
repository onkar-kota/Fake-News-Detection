# Fake-News-Detection

There was a major problem with Twitter on July 15 (yesterday while I’m writing this), big accounts were hacked and asked for bitcoin donations promising to double the sent amount. So even though the tweets were real, they contained fake information.

# Problem
The problem is not only hackers, going into accounts, and sending false information. The bigger problem here is what we call “Fake News”. A fake are those news stories that are false: the story itself is fabricated, with no verifiable facts, sources, or quotes.

The problem is real and hard to solve because the bots are getting better are tricking us. Is not simple to detect when the information is true or not all the time, so we need better systems that help us understand the patterns of fake news to improve our social media, communication and to prevent confusion in the world.

## Solving the problem with Python

1. Load the data in jupyter notebook
2. Data Cleansing

    * Removing title
    * removing puntuations
    * Convert the text to lowercase
    * removing stop words
    
3. Data Exploration

    * word cloud for fake news
    * word cloud for real news
    
4. Modeling

    * The modeling process will consist of vectorizing the corpus stored in the “text” column, then applying TF-IDF, and finally a classification machine learning algorithm. Pretty standard in text analytics and NLP.
    
## Using Logistic Regression we got an accuracy of 98.76%. and confusion matrix
![1_jeiXJmQZQ3hDWN8H0ICrCA](https://user-images.githubusercontent.com/78654246/181072518-6fd5e245-c78e-4bc5-8015-a133226126d6.png)
    
## Using Decision Tree Classifier we got an accuracy of 99.71 %
![1_uA4nhI1z1VntV-y8fxJeaA](https://user-images.githubusercontent.com/78654246/181073157-dfcd7159-e842-4242-9719-6df61b46fb93.png)

## Using Random Forest Classifier we got an accuracy of 98.98 %
![1_Z_CGD_xlW_GNjAsS_yQqkA](https://user-images.githubusercontent.com/78654246/181073444-a540d18a-efea-4ba3-af78-7747a5c64065.png)

 

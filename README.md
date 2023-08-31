# sentiment_analysis
Machine Learning | Natural language processing (NLP) | Random Forests | Bag Of Words | Python
Sentiment Analysis, as the name suggests, it means to identify the view or emotion behind a situation. It basically means to analyze and find the emotion or intent behind a piece of text or speech or any mode of communication. 
We, humans, communicate with each other in a variety of languages, and any language is just a mediator or a way in which we try to express ourselves. And, whatever we say has a sentiment associated with it. It might be positive or negative or it might be neutral as well.
Suppose, there is a fast-food chain company and they sell a variety of different food items like burgers, pizza, sandwiches, milkshakes, etc. They have created a website to sell their food and now the customers can order any food item from their website and they can provide reviews as well, like whether they liked the food or hated it.

User Review 1: I love this cheese sandwich, it’s so delicious.
User Review 2: This chicken burger has a very bad taste.
User Review 3: I ordered this pizza today.
So, as we can see that out of these above 3 reviews,
The first review is definitely a positive one and it signifies that the customer was really happy with the sandwich.

The second review is negative, and hence the company needs to look into their burger department.

And, the third one doesn’t signify whether that customer is happy or not, and hence we can consider this as a neutral statement.

By looking at the above reviews, the company can now conclude, that it needs to focus more on the production and promotion of their sandwiches as well as improve the quality of their burgers if they want to increase their overall sales.
But, now a problem arises, that there will be hundreds and thousands of user reviews for their products and after a point of time it will become nearly impossible to scan through each user review and come to a conclusion.
Therefore, this is where the Sentiment Analysis Model comes into play, which takes in a huge corpus of data having user reviews and finds a pattern and comes up with a conclusion based on real evidence rather than assumptions made on a small sample of data.

We can even break these principal sentiments(positive and negative) into smaller sub sentiments such as “Happy”, “Love”, ”Surprise”, “Sad”, “Fear”, “Angry” etc. as per the needs or business requirement.
Real-World Example –

There was a time when the social media
services like Facebook used to just have two emotions associated with each post, i.e You can like a post or you can leave the post without any reaction and that basically signifies that you didn’t like it.
But, over time these reactions to post have changed and grew into more granular sentiments which we see as of now, such as “like”, “love”, “sad”, “angry” etc.
This is why we need a process that makes the computers understand the Natural Language as we humans do, and this is what we call Natural Language Processing(NLP). And, as we know Sentiment Analysis is a sub-field of NLP and with the help of machine learning techniques, it tries to identify and extract the insights.


Evaluate Dataset
We will use the dataset which is available on Kaggle for sentiment analysis, which consists of a sentence and its respective sentiment as a target variable. This dataset contains 3 separate files named train.txt, test.txt and val.txt.

You can find the dataset here : https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp

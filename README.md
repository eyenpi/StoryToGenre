# StoryToGenre
A simple NLP project for myself.

I used movie dataset from kaggle to train a model that can get a story about a movie
and tell what is its genre.
In this project I used Bag Of Words method. I extracted 1000 words that is most used
in these stories and train a simple deep neural networl using Keras. 
Unfortunatly my final result has a massive overfit on test data. I'm just learning
so I keep it for now and try to fix overfit problem later.

If you want to work on it you should upload your kaggle.json from kaggle API page
and run it from the top. (Only works on linux systems)
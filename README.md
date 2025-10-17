#Simple Python Chatbot
A chatbot that can respond to basic prompts

**Link to project:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/nathanqiuUCSB/Python-Chatbot/blob/main/Chatbot.ipynb)

## How It's Made:

This was my first project experimenting with an AI model and neural networks. Taking a json file with a bunch of text patterns and corresponding tags, I used the bag of words model and lemmatization to break down all the text patterns into an array of all the roots. Then, when taking some input, I transferred it into an array of 1s and 0s with 1s corresponding to a roots present in the input. For the desired outputs, I had one-hot encoded the tags for the different text patterns. Finally, I used the Keras sequential model, the categorial cross entropy loss function, and the Adam optimizer to train and fit the data. From there, I took user's input and sent it through the model, which predicts which tag most likely fits the input and then randomly chooses a response corresponding to the tag.   

## Lessons Learned:

While this chatbot is extremely basic and limited, I was able to learn a lot and understand the foundations of Large Language models and NLP. I learned how to take text data and convert it into something computer's can easily read using lemmatization and the bag of words model. I also learned how to train a data model to take inputs and spit out the most likely output. Finally, I learned how a loss function is used in a model to minimize the loss and create the most accurate model. 

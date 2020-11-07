# Chatbot
## Description

I will show you how you can easily create a powerful chatbot to handle 1) your growing customer requests and inquiries, and 2) communication in different languages.
 
I will also show you how to deploy your chatbot to a web application using Flask.

Feel free to read the post I published on Towards Data Science<br/>
https://towardsdatascience.com/beginners-guide-to-creating-a-powerful-chatbot-48fc6b073e55

## File Descriptions
Chatbot Notebook.ipynb: Jupyter notebook used to develop chatbot<br/>
chatbot_training.py: chatbot training file<br/>
chatbot.py: executable chatbot file<br/>
web_app.py: Flask web application file<br/>

## Instructions
1. pip install chatterbot
2. pip install chatterbot_corpus
3. pip install spacy
4. python -m spacy download en
5. save your conversation text files in **training_data** folder
6. run **chatbot_training.py**
7. run **chatbot.py**
8. run **web_app.py** to deploy chatbot to web app using Flask.

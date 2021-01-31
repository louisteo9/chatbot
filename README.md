# Chatbot
## Table of Contents
1. [Introduction](https://github.com/louisteo9/chatbot#introduction)
2. [File Description](https://github.com/louisteo9/chatbot#file-description)
3. [Installation](https://github.com/louisteo9/chatbot#installation)
4. [Instructions](https://github.com/louisteo9/chatbot#instructions)
5. [Acknowledgement](https://github.com/louisteo9/chatbot#acknowledgement)
6. [Screenshots](https://github.com/louisteo9/chatbot#screenshots)

## Introduction

In this project, I will show you how you can easily create a powerful chatbot to handle your growing customer requests and inquiries.
 
I will also show you how to deploy your chatbot to a web application using Flask.

Feel free to read the post I published on Towards Data Science [here](https://towardsdatascience.com/beginners-guide-to-creating-a-powerful-chatbot-48fc6b073e55)<br/>

## File Description
**Chatbot Notebook.ipynb** - Jupyter notebook used to develop chatbot<br/>
**chatbot_training.py** - chatbot training script<br/>
**chatbot.py** - chatbot script<br/>
**web_app.py** - Flask web application<br/>

## Installation
Please install chatterbot, chatterbot_corpus and spacy if you had not done so. Apart from that, there should be no extra libraries required to install apart from those coming together with Anaconda distribution. The code should run with no issues using Python versions 3.5 and above.

#### Libraries used
chatterbot, os, flask 

## Instructions
1. Install ChatterBot library.<br/>
    `pip install chatterbot`
2. The ChatterBot text corpus is distributed in its own Python package, so you need to install it separately.<br/>
    `pip install chatterbot_corpus`
3. If you have not installed **spaCy** (an open source library for advanced NLP) before, then please install it now because CHatterBot library needs it to work.<br/>
    `pip install spacy`
4. Install spaCy **English** ('en') model after installing the spaCy library.<br/>
    `python -m spacy download en`
5. Save your conversation text files in **training_data** folder.<br/>
6. Run **chatbot_training.py** to train your chatbot. You will be asked to choose if you want to train the chatbot with English corpus data - select **Y** or **N**.<br/>
   (Select **Y** - your chatbot will be trained to have conversations in the following scope: *AI, botprofile, computers, conversations, emotion, food, gossip, greetings, health, history, humor, literature, money, movies, politics, psychology, science, sports & trivia.*)
7. Run **chatbot.py** to launch chatbot in terminal. You can input some conversations and test if it responds properly.<br/>
8. Run **web_app.py** to deploy chatbot to web app using Flask.<br/>

## Acknowledgement
[ChatterBot](https://chatterbot.readthedocs.io/en/stable/) for creating such a powerful chatbot library.

## Screenshots
1. Run **chatbot_training.py** to train your chatbot.<br/>
![](https://github.com/louisteo9/chatbot/blob/main/screenshots/run%20chatbot_training.gif)

2. Run **chatbot.py** to launch chatbot in terminal. Input some conversations and test if it responds properly.<br/>
![](https://github.com/louisteo9/chatbot/blob/main/screenshots/run%20chatbot.gif)

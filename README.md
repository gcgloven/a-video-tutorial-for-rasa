# a-video-tutorial-for-rasa
## What is Rasa about?
Rasa is an open-source chatbot development framework which consists of 2 parts. Natural Language Understanding (rasa_nlu) and Dialogue Management (rasa_core). You may use the NLU part alone for intent classification or entity extractions and other Natural Language Processing Pipelines. 

## What is this tutorial about?
Personally, I still a tech newbie, the purpose of this tutorial is to guide new users to learn rasa and join the open-source community. I am still learning many basic things. I picked up SQL because I was learning rasa. This could also be a good project for me to learn cloud hosting and more sophisticated language understanding pipeline. Also, due to the frequent update from rasa, many old tutorial videos (before rasa 1.0.0) are obsolete or more obscure to understand.

*Things this tutorial would be covering*
1. Learn Basic of Rasa 
2. Integrate Rasa with Telegram 
3. Implement Custom Actions
4. Contextual Writing of your 'stories'
5. Implement SQL storage for rasa Tracker_store(you will know this later)

For future updates, I may include Heroku hosting of webchat, customised NLU component, Rasa HTTP request.

## Why do I choose rasa  
There are many other chatbot development platforms out there such as Dialogflow, IBM Watson, Wit.ai, LUIS, Recast.ai (now bought over by SAP.). These are all drag-and-drop development platforms with a simple RESTful API connection.
However, I still choose rasa, because.
- It's free and Open Source
- It's constantly improving and making things better 
- The developers are super active in the community chat 
- Rasa is highly customisable
- I actually code here and learn about NLP

## For the first part of the tutorial, you may follow me on the rasa website
https://rasa.com/docs/getting-started/


Useful tips when you face problem when develop in Linux:

### How to Virtual Env
https://gist.github.com/frfahim/73c0fad6350332cef7a653bcd762f08d

### Build Wheel Failed on Linux system
sudo apt-get install build-essential
sudo apt-get install libevent-dev
sudo apt-get install python-dev -y
sudo apt-get install python3-dev -y 
sudo apt-get install libevent-dev -y 
sudo apt-get install gcc
sudo apt-get install python3.6-dev // if you are using python 3.6 

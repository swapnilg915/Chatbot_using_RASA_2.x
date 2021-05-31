# Chatbot_using_RASA_2.x

This repo contains the python code and instructions to create your own chatbot / conversational assistant using RASA 2.X
Here I have created a health assistant chatbot. I have already created intents and entities, wrote a python script, and trained a model (available in models directory).

#Installation:
1. create a python virtual environment : python3.7 -m venv rasa_env
2. activate the environment: source rasa_env/bin/activate
3. install rasa: pip install rasa

#setup
1. initialize RASA: rasa init
2. train default model: rasa train
3. After creating intents and entities train the model again: rasa train
4. rasa shell
5. To play with your assistant in CLI: rasa interactive
6. In a new terminal run action server (after making changes to actions.py): rasa run actions
7. Run rasa in CLI: rasa shell

Note: I have followed Rasa for begginers course as suggested on RASA offical website.

#References: 
https://rasa.com/
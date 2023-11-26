# Chatbot_For_College
I have created a Chatbot for my College, where a chatbot can give response to the questions asked by the user. I have used NLU for training a bot.

#To run chatbot_rasa
conda activate clg_chatbot
cd d:/Clg_Chatbot/chatbot_rasa
rasa train
rasa run -m models --enable-api

#To run chatbot_ui
conda activate clg_chatbot
cd d:/Clg_Chatbot/chatbot_ui
python .\__init__.py


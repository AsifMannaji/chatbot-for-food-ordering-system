Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.


Description: A chatbot for food ordering systems utilizing Natural Language Processing (NLP) enables users to effortlessly place orders using natural language. The chatbot interprets user input, navigates menu options, and manages orders, calculating totals and confirming orders. With integration capabilities, it can facilitate payment processing and personalize recommendations. By leveraging NLP libraries and integrating with food ordering systems and databases, this chatbot streamlines the ordering process, enhancing customer experience and efficiency. It can be applied to food delivery platforms or restaurant websites, making food ordering more convenient and user-friendly.

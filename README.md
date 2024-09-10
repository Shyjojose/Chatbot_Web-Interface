# Chatbot_Web-Interface
python3.11 -m pip install flask
python3.11 -m pip install flask_cors
python3.11 -m pip install transformers torch
curl -X POST -H "Content-Type: application/json" -d '{"prompt": "Hello, how are you today?"}' 127.0.0.1:5000/chatbot

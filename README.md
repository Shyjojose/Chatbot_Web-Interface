# Chatbot_Web-Interface<br />
Set up your back-end server<br />
Integrate your chatbot into your Flask server<br />
Communicate with the back-end using a web page<br />
<br />
python3.11 -m pip install flask<br />
python3.11 -m pip install flask_cors<br />
python3.11 -m pip install transformers torch<br />
curl -X POST -H "Content-Type: application/json" -d '{"prompt": "Hello, how are you today?"}' 127.0.0.1:5000/chatbot<br />
flask run 

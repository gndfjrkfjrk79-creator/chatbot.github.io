<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>AI Chatbot</title>
<style>
    body { font-family: Arial; max-width: 600px; margin: auto; padding: 20px; }
    #chatbox { border: 1px solid #ccc; padding: 10px; height: 400px; overflow-y: auto; }
    .user { color: blue; margin: 5px 0; }
    .bot { color: green; margin: 5px 0; }
    #inputArea { display: flex; margin-top: 10px; }
    #message { flex: 1; padding: 10px; }
</style>
</head>
<body>

<h2>AI Chatbot</h2>

<div id="chatbox"></div>

<div id="inputArea">
    <input type="text" id="message" placeholder="Type your message...">
    <button onclick="sendMessage()">Send</button>
</div>

<script src="chat.js"></script>
</body>
</html>

# SimpleChatbot
# Python Chatbot

This is a simple chatbot implemented in Python.

## Features

* Greets the user with a random greeting.
* Responds to "how are you?"
* Responds to the user's name.
* Says goodbye.
* Handles unknown input with a default message.
* Uses regular expressions for more flexible pattern matching.

## How to Use

1.  Run the code.
2.  The chatbot will start the conversation.
3.  Type your input in the console.
4.  The chatbot will respond.
5.  Type "bye", "goodbye", or "see you" to end the conversation.

## Code Structure

* `Chatbot` class:
    * `__init__(self)`:  Initializes the chatbot with greetings, farewells, responses to "how are you", unknown responses, and the user's name.
    * `greet(self)`: Returns a random greeting.
    * `farewell(self)`: Returns a random farewell message.
    * `ask_how_are_you(self)`: Returns a random response to "how are you?".
    * `respond_to_name(self, name)`: Stores the user's name and returns a personalized greeting.
    * `handle_unknown(self)`: Returns a random response for unknown input.
    * `respond(self, user_input)`:  Processes the user's input using regular expressions and returns an appropriate response.
    * `start_chat(self)`:  Starts the chatbot interaction loop.

## Dependencies

* Python 3
* `random` module (built-in)
* `re` module (built-in)

## To Run the Chatbot

1.  Save the code as a Python file (e.g., `chatbot.py`).
2.  Open a terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Run the script using:  `python chatbot.py`

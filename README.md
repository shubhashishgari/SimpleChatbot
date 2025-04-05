# Simple Chatbot
# Java Chatbot

This is a simple chatbot implemented in Java.

## Features

* Greets the user with a random greeting.
* Responds to "how are you?"
* Responds to the user's name.
* Says goodbye.
* Handles unknown input with a default message.

## How to Use

1.  Compile the Java code (e.g., using a Java compiler like `javac`):
    ```bash
    javac Chatbot.java
    ```
2.  Run the compiled code:
    ```bash
    java Chatbot
    ```
3.  The chatbot will start the conversation.
4.  Type your input in the console.
5.  The chatbot will respond.
6.  Type "bye", "goodbye", or "see you" to end the conversation.

## Code Structure

* `Chatbot` class:
    * `greetings`, `farewells`, `howAreYouResponses`, `unknownResponses`:  Arrays of possible chatbot responses.
    * `name`:  Stores the user's name.
    * `random`:  A `Random` object for generating random numbers.
    * `greet()`: Returns a random greeting.
    * `farewell()`: Returns a random farewell message.
    * `askHowAreYou()`: Returns a random response to "how are you?".
    * `respondToName(String name)`: Stores the user's name and returns a personalized greeting.
    * `handleUnknown()`: Returns a random response for unknown input.
    * `respond(String userInput)`: Processes the user's input and returns an appropriate response.
    * `startChat()`: Starts the chatbot interaction loop.
    * `main(String[] args)`: The main method to create a `Chatbot` object and start the chat.

## Dependencies

* Java Development Kit (JDK)

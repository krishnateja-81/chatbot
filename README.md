# Streamlit Chatbot with OpenAI GPT Integration

This repository contains a Streamlit web application that integrates OpenAI's GPT-3.5 model to create a conversational chatbot interface. The chatbot allows users to interact with the GPT model by sending messages and receiving responses in real-time.

## Features

- **Chat Interface**: Users can send messages to the chatbot through a simple input field.
- **Real-time Responses**: The chatbot processes user messages using OpenAI's GPT model and provides responses in real-time.
- **Role-based Messaging**: Messages are displayed with different avatars indicating whether they are from the user or the chatbot.
- **Error Handling**: The application gracefully handles errors, such as server congestion, and provides appropriate feedback to the user.

## How to Use

1. Ensure you have the necessary dependencies installed (`openai`, `streamlit`).
2. Set up your OpenAI API key by replacing `api_key = ""` with your actual API key.
3. Run the Streamlit application using `streamlit run <filename>.py`.
4. Interact with the chatbot by typing messages in the input field and observing the responses.

## Notes

- You may need to adjust the `openai_model` variable to use a different GPT model variant depending on your preference and available resources.
- Feel free to customize the avatars, styling, and additional features of the chat interface to suit your needs.

This project provides a simple yet powerful example of integrating conversational AI capabilities into web applications using Streamlit and OpenAI's GPT model.

![Streamlit Chatbot](https://github.com/krishnateja-81/chatbot/blob/master/chatbot.png)

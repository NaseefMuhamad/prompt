# Conversational AI Chatbot with Gemini API

This project is a simple conversational assistant built using Google's Gemini API. It maintains a conversation history, handles user commands like `save` and `summary`, and includes error handling and word count constraints for assistant replies.

## Background

Initially, I implemented this chatbot using the OpenAI API. However, due to access limitations or quota issues, I was unable to proceed with OpenAI's service. As a result, I switched to Google's Gemini API, which offers similar capabilities for generating conversational responses. The logic and structure remained largely the same—only the backend model changed.

## Features

- Maintains full conversation history
- Handles empty input gracefully
- Limits assistant replies to 15–50 words
- Saves conversation to a `.txt` file when user types `save`
- Summarizes the conversation when user types `summary`
- Retries API calls up to 3 times on failure

# Customer Support Chatbot with Sentiment Detection

Google Colab Notebook link: [Open Notebook](https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?usp=sharing)

## Project Overview

This project involves creating a customer support chatbot with sentiment detection. The chatbot utilizes a dataset of predefined questions and answers, and employs the Llama 2 model from Hugging Face for generating responses. Sentiment analysis is integrated to provide context-aware responses based on the user's emotional state.

### Key Features:
- **Sentiment Detection**: The chatbot analyzes user input to detect frustration or satisfaction and adjusts its responses accordingly.
- **Dynamic Responses**: If a question is not found in the predefined dataset, the chatbot generates a response using Llama 2.
- **Continuous Learning**: New question-answer pairs are added to the dataset based on user interactions.

### Examples:
- **User Input**: "I feel angry"
  - **Response**: "I'm sorry you're feeling frustrated. What’s making you angry?"

- **User Input**: "I’m happy with the service"
  - **Response**: "I'm glad you're feeling satisfied! How can I assist you further?"

# Customer Support Chatbot with Sentiment Detection

Google Colab Notebook link: [Open Notebook](https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?usp=sharing)

## Project Overview

The **Customer Support Chatbot with Sentiment Detection** is designed to enhance customer service interactions by incorporating sentiment analysis into the chatbot's responses. This project leverages advanced natural language processing (NLP) techniques and machine learning models to detect user emotions and adjust responses accordingly, aiming to improve overall user satisfaction and support quality.

### Key Features:
1. **Sentiment Detection**:
   - Utilizes sentiment analysis to determine whether user input reflects frustration, satisfaction, or neutrality.
   - Tailors responses based on detected sentiment to address user emotions appropriately.

2. **Dynamic Answer Generation**:
   - If a user’s question is not found in the predefined dataset, the chatbot generates a response using the Llama 2 model.
   - This allows the chatbot to handle a wide range of questions and provide relevant information even when specific queries are not predefined.

3. **Continuous Learning**:
   - New question-answer pairs are added to the dataset based on user interactions.
   - This feature ensures that the chatbot becomes more accurate and useful over time by learning from new queries and responses.

### How It Works:
- **Sentiment Analysis**: The chatbot uses a sentiment analysis model to classify user input as either positive, negative, or neutral. Depending on the detected sentiment, it adjusts its response to be empathetic or supportive.
- **Question-Answer Matching**: It first checks if the question is present in the predefined dataset. If found, it retrieves the corresponding answer. If not, it generates an answer using the Llama 2 model and adds the new question-answer pair to the dataset.
- **Response Adjustment**: Based on the sentiment detected, the chatbot provides a tailored response. For negative sentiments, it might offer an apology or inquire further about the user’s concerns. For positive sentiments, it might express satisfaction or offer further assistance.

### Examples:
- **User Input**: "I feel angry from the service"
  - **Response**: "I'm sorry you're feeling frustrated. What’s making you angry?"

- **User Input**: "I’m happy with the service"
  - **Response**: "I'm glad you're feeling satisfied! How can I assist you further?"

### Usage Instructions:
1. **Access the Google Colab Notebook**: Click on the [Google Colab link](https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?usp=sharing) to view and interact with the notebook.
2. **Run the Notebook**: Execute the cells in the notebook to initialize the chatbot and start interacting with it.
3. **Try Different Inputs**: Test the chatbot by entering various questions and observe how it handles different sentiments.


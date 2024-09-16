# Customer-Support-Chatbot-with-Sentiment-Detection


Google Colab Notebook link: [https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?authuser=0#scrollTo=17czJpk-Kob6](https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?authuser=0#scrollTo=17czJpk-Kob6)

## Project Overview

The **Customer Support Chatbot with Sentiment Detection** is designed to improve customer interactions by integrating sentiment analysis into its response system. This chatbot leverages advanced natural language processing (NLP) techniques to assess user sentiment and tailor responses accordingly. Built using the Llama 2 model from Hugging Face, this chatbot can provide contextually relevant answers based on both predefined Q&A data and generative responses.

### Key Features:

1. **Sentiment Detection**: The chatbot can identify user sentiments such as frustration or satisfaction. This is achieved through sentiment analysis models that evaluate the emotional tone of user inputs.
   
2. **Dynamic Response Generation**: Depending on the detected sentiment, the chatbot adjusts its responses. For instance, if the sentiment is negative, the chatbot will apologize and offer additional support. Positive sentiments are met with more informative and helpful responses.

3. **Predefined Q&A Integration**: The system includes a predefined Q&A dataset that it uses to provide accurate answers to frequently asked questions. If a question is not found in the dataset, the chatbot utilizes the Llama 2 model to generate a suitable response.

4. **Gradio Interface**: A user-friendly Gradio interface allows for real-time interaction with the chatbot. Users can type in their questions, and the chatbot will respond based on the sentiment detected and the available data.

### Example Interactions:

1. **Question**: "I'm really frustrated with the service I received. Can you help me with my issue?"
   - **Chatbot Response**: "I'm really sorry to hear that you're frustrated. Please provide more details about your issue, and I'll do my best to assist you."

2. **Question**: "What are your operating hours?"
   - **Chatbot Response**: "Our operating hours are Monday to Friday, 9 AM to 6 PM. If you have any other questions, feel free to ask!"

3. **Question**: "I had a great experience with your service. Thank you!"
   - **Chatbot Response**: "Thank you for your positive feedback! We're glad to hear that you had a great experience. If there's anything else you need, just let us know."

### How It Works:

1. **Initialization**: The chatbot initializes by loading the Llama 2 model and tokenizer from Hugging Face. This model is used for generating responses based on user queries.
   
2. **Question Handling**: When a question is posed, the chatbot first checks if the question exists in the predefined Q&A dataset. If a match is found, the corresponding answer is provided.

3. **Sentiment Analysis**: If the question is not in the dataset, the chatbot generates a response using the Llama 2 model. During this process, sentiment analysis is performed to determine the emotional tone of the response.

4. **Response Adjustment**: Based on the detected sentiment, the response is adjusted. For negative sentiments, the chatbot includes an apology and offers further assistance. For positive sentiments, the response is more informative and engaging.

5. **Continuous Learning**: The chatbot updates its Q&A dataset with new question-answer pairs as they are generated. This helps in continuously improving the accuracy and relevance of the responses.

### Technical Details:

- **Libraries Used**: `transformers`, `torch`, `gradio`, `pandas`
- **Model**: Llama 2 from Hugging Face
- **Sentiment Analysis**: Integrated with Hugging Face's sentiment analysis models
- **Deployment**: Gradio interface for easy user interaction

This project aims to provide a seamless and responsive customer support experience by combining advanced NLP techniques with practical sentiment analysis. The resulting chatbot not only answers questions but also understands and responds empathetically to user emotions, making it a valuable tool for enhancing customer satisfaction.

For more details and to interact with the chatbot, you can access the [Google Colab Notebook](https://colab.research.google.com/drive/1wlQfBtIx-rP__7trPvQG5Agvbk0s776r?authuser=0#scrollTo=17czJpk-Kob6).

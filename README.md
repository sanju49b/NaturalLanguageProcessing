### #TwitterSentimentClassification

This project utilizes Hugging Face's transformer models to classify the sentiment of tweets. The model is fine-tuned for multi-class sentiment classification, focusing on categorizing tweets based on their emotional tone, such as joy, sadness, anger, etc. The model achieves an accuracy of around 90%.

To interact with the model, a Streamlit-based web application is developed as the front end. Users can input their tweets via the Streamlit interface, which sends the data to the backend model for classification. Once the model processes the tweet, the predicted sentiment and its associated confidence score are displayed on the Streamlit application.

Key Steps:
1. **Data Preparation**: Tweets are preprocessed and tokenized using Hugging Face’s `AutoTokenizer` for text data transformation.
2. **Model Building**: A transformer model, specifically BERT, is fine-tuned for sentiment classification.
3. **Streamlit Interface**: The front-end application allows users to submit tweets and view the predictions on the fly.

This project demonstrates the integration of NLP models with interactive web applications, making sentiment analysis accessible to users in real-time.

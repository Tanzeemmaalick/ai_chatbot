# ai_chatbot
# College Enquiry Chatbot

![College Enquiry Chatbot](chatbot.png)

The College Enquiry Chatbot is a simple Python-based chatbot that can answer questions related to a college. The chatbot uses natural language processing techniques and a trained deep learning model to understand user queries and provide relevant responses.

## How to Use

1. Clone the project repository:

   ```
   git clone https://github.com/your-username/college-enquiry-chatbot.git
   cd college-enquiry-chatbot
   ```

2. Make sure you have the required libraries installed:

   ```
   pip install nltk tensorflow
   ```

3. Run the chatbot:

   ```
   python chatbot.py
   ```

4. The chatbot will greet you and invite you to ask questions about the college.

## Features

- The chatbot is trained on a set of predefined intents (questions) and responses specific to the college domain.
- The chatbot uses the `nltk` library for natural language processing.
- It uses a deep learning model built with TensorFlow to classify user queries and generate appropriate responses.

## Files and Data

- `intents.json`: A JSON file containing predefined intents and responses for the chatbot.
- `words.pkl` and `classes.pkl`: Pickle files storing tokenized words and classes used for training the model.
- `chatbotmodel.h5`: The trained deep learning model for intent classification.

## How it Works

1. User input is processed to identify the intent of the query using the trained model.
2. The chatbot matches the intent to predefined intents and selects a relevant response.
3. The response is returned to the user.

## Customization

To customize the chatbot for your own college or domain, modify the `intents.json` file with your specific intents and responses. You can also retrain the deep learning model using your own data if needed.

## Requirements

- Python 3.x
- `nltk` library
- TensorFlow 2.x

## Contributions

Contributions to the project are welcome. If you have any suggestions or find any issues, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE.md).

Thank you for using the College Enquiry Chatbot. We hope it provides helpful information about our college and enhances your experience!

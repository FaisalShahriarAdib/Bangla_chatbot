Libraries:
Numpy: Utilized for numerical computations, particularly in data preprocessing.
NLTK (Natural Language Toolkit): Employed for natural language processing tasks such as tokenization and lemmatization.
TensorFlow-Keras: Used for building, training, and deploying deep learning models, in this case, for the chatbot.
Random: Used for generating random responses within the chatbot.
JSON: Utilized for handling data stored in JSON format.
Pickle: Employed for serializing and deserializing Python objects, used here for storing trained model parameters.


Key Features:
Interactive Chat: The chatbot interacts with users, responding to their messages based on predefined intents and responses stored in a JSON file.
NLP-Based Responses: Utilizes a deep learning model trained on tokenized and lemmatized input sentences to predict appropriate responses.
Dynamic Learning: The model is trained on the fly as new data is provided, enabling it to adapt and improve its responses over time.
Learning Rate Schedule: Utilizes a learning rate decay schedule during model training to improve convergence and performance.
Model Persistence: Trained model parameters are saved to disk for future use, ensuring the chatbot's state is maintained across sessions.

youtube link: https://youtu.be/U93It3AUXCE
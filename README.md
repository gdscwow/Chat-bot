# Chat-bot

I have created a chatbot that is trained on a comprehensive dataset using TensorFlow. The dataset is in the form of a JSON file, which contains tags associated with customer questions and predefined answers.

The chatbot utilizes the softmax function, which converts an input vector of real numbers into a probability distribution, representing the likelihood of different outcomes, it has 4 layers, each with 8 nodes, trained for 1000 epochs. 

The chatbot also has a unique feature, when the event that the model is unable to predict the customer's query, the chatbot responds with the message "Can you please elaborate on your query." To further improve the model's performance, I am using Google Cloud Storage to store these unanswered questions in a text format, and then collecting and retraining the model with this new data.

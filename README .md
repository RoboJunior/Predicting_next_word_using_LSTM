
# Predicting next word using LSTM

In this GitHub project, I developed an LSTM-based language model to predict the next word in a sentence using Shakespearean plays as training data. The goal was to create a chatbot or conversational agent capable of generating contextually appropriate responses in Shakespearean language.

# Approach

**Data Preparation:** I preprocessed the Shakespeare play text by removing all punctuations and converting the words to lowercase. The text was then tokenized to create a sequence of words for training.

**Model Architecture:** I implemented a Long Short-Term Memory (LSTM) neural network, known for its effectiveness in capturing sequential dependencies in data. The model also included dense layers with softmax and ReLU activation functions for enhanced learning.

**Training:** The LSTM model was trained for 100 epochs using a GPU to leverage its computational power, as deep learning models typically require significant resources for efficient training.

**Word Prediction:** The training data was split into sequences of 50 words with one word predicted at a time. By tokenizing the word sequence, the model was trained to predict the subsequent word given the previous context.

# Results
The LSTM-based language model achieved promising results in predicting the next word in Shakespearean language. The training process took approximately 1.5 hours, thanks to the utilization of a GPU.

# Future Work:
In the future, I plan to experiment with different model architectures, such as Transformer-based models, to further improve the chatbot's performance and adaptability. Additionally, exploring larger datasets and fine-tuning the model on domain-specific Shakespearean text might enhance its ability to generate more contextually appropriate responses.

Overall, this project serves as a solid foundation for building advanced language models for various conversational applications, and the code and preprocessed data are available in the GitHub repository for further exploration and contributions.
## Support

For support, email jeyaramanjr7@gmail.com.


## Related

Here are some related projects

[AI Tools](https://github.com/RoboJunior/AI-Tools)

[Voice Assistant AI](https://github.com/RoboJunior/Voice_Assistant_Ai)

[Junior Data Scientist](https://github.com/RoboJunior/Junior_DataScientist)

Make sure check it out ☝️
![Logo](https://i.ibb.co/H7xm81X/Robo-Junior.png)


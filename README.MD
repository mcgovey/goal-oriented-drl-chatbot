# Goal-Oriented-DRL-Chatbot
Goal Oriented Chatbot implemented using Deep Reinforcement Learning in Python. This chatbot uses deep q networks to build a chatbot that is able to interact with users and get data about restaurant reservations.

This chatbot does not use natural language, instead focusing on the goal-oriented reinforcement learning aspect of the agent.

## Data
The data used for this model is a selection of 15 random restaurants from New York. The user requests are generated randomly from this dataset and the number of open slots are also generated randomly. All data generation can be seen in the file `gen_data_for_chatbot.ipynb`.

## Dependencies 
- Python >= 3.5
- Keras >= 2
- numpy

## Changing parameters
There are a number of constants that can be changed in the file `constants.json`. Some of which include `num_ep_run` and `load_weights_file_path`.

## To run
To train the agent you'll need to run `python train.py`.

Additionally, you can test the trained model by setting `load_weights_file_path` and running `python test.py`.

## References
Base code taken from [Goal-Oriented Chatbot DRL Example](https://github.com/maxbren/GO-Bot-DRL) and the paired [medium article](https://towardsdatascience.com/training-a-goal-oriented-chatbot-with-deep-reinforcement-learning-part-i-introduction-and-dce3af21d383). The license file reflects this usage.
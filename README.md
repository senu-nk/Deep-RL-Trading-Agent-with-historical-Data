# Deep-RL-Trading-Agent-with-historical-Data
Deep Reinforcement Learning agent with a basic Deep neural network to Buy/Sell using historical price Data.

Methods:
* _build_model: Making new model.
* load: Loading a trained model's weights and biases.
* save: Saving the model's weights and biases.
* remember: Saving the current state, action, reward and the next state.
* replay: Retraining the nuralnet using the recent experience.
* act: Deciding next action.(predicting the next best action using the predicted reward or take a random action.)

Conclusion:
Even though there was a visible improvement in the average score of the model, the model doesn't seem to be passing a certain score level. Hence the training process was aborted after 940 episodes.

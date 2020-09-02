# BoxingV0-StableBaselines
An implementation of a DQN trained on Openai Gym's boxing-v0-ram using Stable Baselines. Credit goes to [StarAI](https://www.starai.io/course/) for Colab visualization code.

The agent is playing the white character below:

<img src = "https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/visualization.gif" alt = "An agent trained for 200,000 episodes beats the built-in AI handily." width = "400">

## How well does it do?

![](https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/training_rewards.png?raw=true)

It starts beating the built-in AI reliably after around the 70,000th episode.

Unfortunately, training got really unreliable (probably because of the vanilla DQN architecture) and performance varied a lot from episode to episode.

The highest-performing agent (saved on episode 149,000) achieved an average score of 40.54 over 37 test episodes.

===========
## Training
Want to train your own agent?
Run the ipython file [here](https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/Stable_Boxing.ipynb). Click the link to Google Colab [here](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667) or on the ipython page to train the agent directly on Colab.

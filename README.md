# BoxingV0-StableBaselines
An implementation of a DQN trained on Openai Gym's boxing-v0-ram using Stable Baselines. 

The agent is playing the white character below:

<img src = "https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/visualization.gif" alt = "An agent trained for 200,000 episodes beats the built-in AI handily." width = "300">


## How well does it do?

![](https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/training_rewards.png?raw=true)

It starts beating the built-in AI reliably after around the 70,000th episode.

Unfortunately, training got really unreliable (probably because of the vanilla DQN architecture) and performance varied a lot from episode to episode.

The highest-performing agent (saved on episode 149,000) achieved an average score of 40.54 over 37 test episodes.


## Training
Want to train your own agent?
- ``git clone`` this repository and run the ipython file [here](https://github.com/wz-ml/BoxingV0-StableBaselines/blob/master/Stable_Boxing.ipynb).

---

Alternatively:
- Click [here](https://colab.research.google.com/github/wz-ml/BoxingV0-StableBaselines/blob/master/Stable_Boxing.ipynb) to access the colab file directly.
- Click file -> open in playground -> run all.


## Credits
Credit goes to [StarAI](https://www.starai.io/course/) for Colab visualization code.
Check out the [Stable Baselines](https://stable-baselines.readthedocs.io/en/master/) library for awesome reinforcement learning algorithms!


## License
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
- **[Apache 2.0 License](https://opensource.org/licenses/Apache-2.0)**

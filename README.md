# Asynchronous Methods for Deep Reinforcement Learning

## Reference
### Paper
- Link: https://arxiv.org/abs/1602.01783

### Original Code
- Link: https://github.com/miyosuda/async_deep_reinforce
- Asynchronous Advantage Actor-Critic (A3C) method for playing "Atari Pong" is implemented with TensorFlow.

### Modifications
- I copied the branch "gym" and modified it to use in TF 0.12.
- Instead of using Arcade Learning Environment directly, OpenAI gym is utilized.

## How to run
- To train,

    $python a3c.py
- To display the result with game play,

    $python a3c_display.py
   

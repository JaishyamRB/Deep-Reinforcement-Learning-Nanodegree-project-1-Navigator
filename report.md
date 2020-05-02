# Project report

## Learning algorithm

The learning algorithm used is vanilla Deep Q Learning as described in original paper. As an input the vector of state is used instead of an image so convolutional neural nework is replaced with deep neural network. The deep neural network has following layers:

- Fully connected layer - input: 37 (state size) output: 128
- Fully connected layer - input: 128 output 64
- Fully connected layer - input: 64 output: (action size)

Parameters used in DQN algorithm:

- Maximum steps per episode: 1000
- Starting epsilion: 1.0
- Ending epsilion: 0.01
- Epsilion decay rate: 0.999

## Results

![results](images/graph.jpg)

```
Episode 100	Average Score: 0.42
Episode 200	Average Score: 2.74
Episode 300	Average Score: 7.16
Episode 400	Average Score: 10.63
Episode 500	Average Score: 12.34
Episode 599	Average Score: 13.05
Environment solved in 499 episodes!	Average Score: 13.05
```

### Untrained agent

![untrained](images/untrained.gif)

### Trained agent

![trained](images/trained.gif)

## Ideas for future work

1. Extensive hyperparameter optimization
2. Double Deep Q Networks
3. Prioritized Experience Replay
4. Dueling Deep Q Networks
5. RAINBOW Paper
6. Learning from pixels

# Report

This report describes my implementation to solve the banana navigation project.

## Learning Algorithm

The implementation here is a basic Deep Q-Learning Algorithm that is being taught in lesson 2. Some alterations have been done on the second implementation such as changing their hyper-parameters which can be found below.

### First Implementation

**Hyper-Parameters for First Implementation**  
- Replay Buffer Size: 100000
- Batch Size: 64
- Gamma (discount factor): 0.99
- Tau (soft update): 0.005
- Learning Rate: 0.001
- Update Network: 4

The code can be found in `script_1`.

The first implementation is a Deep Q-Learning model with 2 hidden layers. The first hidden layer has 64 neurons with ReLu as activation function. The second hidden layer has also 64 neurons with ReLu as activation function.

The training Results:  
```
Episode 100	Average Score: 6.63
Episode 200	Average Score: 8.17
Episode 300	Average Score: 9.42
Episode 400	Average Score: 10.28
Episode 500	Average Score: 11.03
Episode 600	Average Score: 11.51
Episode 700	Average Score: 11.92
Episode 800	Average Score: 12.20
Episode 900	Average Score: 12.42
Episode 1000	Average Score: 12.53
Episode 1100	Average Score: 12.55
Episode 1200	Average Score: 12.71
Episode 1300	Average Score: 12.83
Episode 1400	Average Score: 12.91
Episode 1500	Average Score: 12.98
Episode 1533	Average Score: 13.00
Environment solved in 1433 episodes!	Average Score: 13.00)
```

Observation:  
It seems that the model learns slower after 600 episodes. Some parameter tuning is needed.

### Second Implementation
**Hyper-Parameters for First Implementation**  
- Replay Buffer Size: 100000
- Batch Size: 128
- Gamma (discount factor): 0.999
- Tau (soft update): 0.005
- Learning Rate: 0.0005
- Update Network: 16

The code can be found in `script_2`.

The second implementation is also a Deep Q-Learning model with 2 hidden layers. The first hidden layer has 128 neurons with ReLu as activation function. The second hidden layer has also 128 neurons with ReLu as activation function.

The Training Results:
```
Episode 100	Average Score: 2.87
Episode 200	Average Score: 6.37
Episode 300	Average Score: 8.29
Episode 400	Average Score: 9.72
Episode 500	Average Score: 10.82
Episode 600	Average Score: 11.58
Episode 700	Average Score: 12.10
Episode 800	Average Score: 12.50
Episode 900	Average Score: 12.93
Episode 928	Average Score: 13.00
Environment solved in 828 episodes!	Average Score: 13.00
```

Observation:  
The model starts learning slower that the previous implementation, however, the learning process is steadier than before. It slows down significantly at around 600 episodes but it is still learning better than the previous implementation.


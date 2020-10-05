# Report

This report describes my implementation to solve the banana navigation project.

## Learning Algorithm

The implementation here is a basic Deep Q-Learning Algorithm that is being taught in lesson 2. Some alterations have been done on the second implementation such as changing their hyper-parameters which can be found below.

**Hyper-Parameters for First Implementation**  
- Replay Buffer Size: 100000
- Batch Size: 64
- Gamma (discount factor): 0.99
- Tau (soft update): 0.005
- Learning Rate: 0.001
- Update Network: 4

I have tried a couple of implementation, the first implementation is in `script_1` whereas the second implememtation is in `script2`.

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

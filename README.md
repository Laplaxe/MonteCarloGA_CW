This is the companion directory for the paper "Critical Role of local Monte Carlo steps in machine-learning-driven Sequential Tempering".
It includes the notebook used to create Figure 1.
In particular, the notebook:

- Generates the probability transition matrix for the local Metropolis MC
- Uses Thomas' algorithm to find the average first-passage times
- Compares the average times required to obtain a configuration of magnetization $|m| \geq |m^*|$ using only global MADE moves and MADE + local Metropolis moves

# Critical Role of local Monte Carlo steps in machine-learning-driven Sequential Tempering

This is the companion directory for the paper "Critical Role of local Monte Carlo steps in machine-learning-driven Sequential Tempering".
It includes the notebook used to create the different figures.
The directory is organized as follows:

- Code: contains the code to obtain the data and make the picture shwn in the article. In particular, it contains 2 notebooks:
- - made_architecture.ipynb: studies the MADE architecture for Curie-Weiss
- - first_passages.ipynb: studies the dynamical part regarding the first passage time comparisons
- Data: contains some of the data required to make the plots (in particular those that require long time to be generated)
- Plots: contains the different plots shown in the article

- Generates the probability transition matrix for the local Metropolis MC
- Uses Thomas' algorithm to find the average first-passage times
- Compares the average times required to obtain a configuration of magnetization $|m| \geq |m^*|$ using only global MADE moves and MADE + local Metropolis moves

This directory does not contain the code to solve the integral equations that appear in the article. These can be straightforwardly solved using e.g. Mathematica.
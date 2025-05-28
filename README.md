# On the performance of machine-learning assisted Monte Carlo in sampling from simple statistical physics models 

This is the companion directory for the paper "On the performance of machine-learning assisted Monte Carlo in sampling from simple statistical physics models ".
It includes the notebook used to create the different figures.
The directory is organized as follows:

- Code: contains the code to obtain the data and make the picture shwn in the article. In particular, it contains 2 notebooks:
  - made_architecture.ipynb: studies the MADE architecture for Curie-Weiss
  - first_passages.ipynb: studies the dynamical part regarding the first passage time comparisons
- Data: contains some of the data required to make the plots (in particular those that require long time to be generated)
- Plots: contains the different plots shown in the article

This directory does not contain the code to solve the integral equations that appear in the article. These can be straightforwardly solved using other software (e.g. Mathematica).

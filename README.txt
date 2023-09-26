This project is an example of Reinforcement Learning. There are four files 1. game.py 2. agent.py 3. model.py 4. helper.py


1. game.py --> It uses python libraries and logical code to for the interface of snake game.
2. agent.py --> It uses set of instruction to act on the environment of snake game. It explores randomly upto 80 games and then afterwards it uses ML models(using pytorch) to predict its next action.
3. model.py --> Model used in this project follows Bellman equation to predict the future moves of snake agent.
4. helper.py --> It uses Matplotlib to plot a graph of scores vs no. of games and mean_scores vs no. of games in same X-Y plane.


Pre-Requistion --> OOPS, ML, Pytorch  
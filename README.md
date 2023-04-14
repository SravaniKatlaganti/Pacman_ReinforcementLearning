# Pacman_ReinforcementLearning


To run Q-learning Pacman for very tiny grids:
```
python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid
```
While a total of 2010 games (-n 2010) will be played, the first 2000 games will not be displayed because of the option -x 2000, which designates the first 2000 games for training (no output). Thus, you will only see Pacman play the last 10 of these games which are for testing.



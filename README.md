# Pacman_ReinforcementLearning

### Run commands:
```
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic
```

#### To run Q-learning Pacman for very tiny grids:
```
python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid
```
While a total of 2010 games (-n 2010) will be played, the first 2000 games will not be displayed because of the option -x 2000, which designates the first 2000 games for training (no output). Thus, you will only see Pacman play the last 10 of these games which are for testing. During training, you will see output every 100 games with statistics about how Pacman is faring.

#### To run Q-learning Pacman for small grids:
```
python pacman.py -p ApproximateQAgent -x 2000 -n 2010 -l smallGrid 
```

#### To run Q-learning Pacman for medium grids:
```
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid
```

#### To run Q-learning Pacman for medium classic grids:
```
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic
```

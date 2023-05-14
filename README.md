# Expected Completions
Calculating the probability of an American Football pass being completed, using NFL Big Data Bowl 2023 Data

## Method: 
Binary classification of Pass Completions using XGBoost, trained on ~7000 pass plays with with Cross Validation by passing team (k = 32)

## Features: 
    ### Spatial: for WR and QB on each play: Speed, Orientation, distance to nearest defender and to each other
    ### Game State: Down, Distance, YardLine, Score, is Possesion team leading the game.

## Metrics:
Accuracy: 0.94
F1 0.92
AUC 0.93


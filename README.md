# Expected Completions
Calculating NFL Expected Completion from BDB23 Data

Method: Binary classification of Pass Completions using XGBoost
Features: 
    Spatial: WR Speed, WR Orientation, WR Distance to QB and nearestDBs
    Game State: Down, Distance, YardLine, Score, is PossesionTeam in the lead

Model is 32 fold Cross Validated, where K is all possessions of one team


# expected_completion
Calculating NFL Expected Completion from BDB23 Data

initial plan: 
GNN where network is all defenders, qb and OL, and receivers, for each receiver
include CPOE metrics, orientation and dir (of WR relative to QB), speed, etc. maybe pressure metric (defender within 1 yard? maybe a PFF pressure metric?)
Cross Validate for team

graph a: pass russ to QB, OL to QB, Coverage to WR (maybe calculate for everyone then clear those)
graph x: qb wr pass rush, pass block, coverage. orientation, dir (relative to qb) s
y: binary pass fail or no
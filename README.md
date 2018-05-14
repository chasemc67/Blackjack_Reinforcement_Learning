### Learning Optimal Blackjack Strategies with Reinforcement Learning


An AI learns the optimal strategy (hit, fold), for every possible card combination.
This learning is done through Reinforcement Learning, and millions of play throughs. 

### Requirements:
```
python 2.7
```

### Installing Requirements:
```
conda create --name python27 python=2.7
source activate python27
```

### Usage:
```
python ExpectedSarsa.py
```

#### Output:
```
 Usable Ace:
S S S H S S H H S S 20
S S H S S S H S S H 19
H S H H H H S S H H 18
H H S H H H H H H H 17
S H H H H H H S H H 16
H H H H H H H S S H 15
H H H H H H H H H H 14
H H H H H H H H H S 13
H H H H H H H H S H 12
1 2 3 4 5 6 7 8 9 10

 No Usable Ace:
S S S S S S S S S S 20
S S S S S S S S S S 19
S S S S S S S S S S 18
H S S S S S S S S S 17
H H S S S H H H H H 16
S S H S H S H H H S 15
H S S H S S H H H H 14
H H H H H H H H H H 13
H H H H H S H H H H 12
1 2 3 4 5 6 7 8 9 10

Avg Return:-0.0685745454545
Settings:
Episodes: 1100000
Drop Epsilon: 10000
Epsilon: 0.01
Alpha: 0.05
```

This is an assignment from a class on Reinforcement Learning, taught by Richard Sutton, the father of Reinforcement Learning

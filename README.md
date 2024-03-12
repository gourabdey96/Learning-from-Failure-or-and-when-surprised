# Learning-from-Failure-or-and-when-surprised
Replay Buffer Algorithm HPER combining HER and PER

This repo reproduces the results of HindSight Experience Replay(HER) in a single-goal RL setting using the Mountain Car environment. Different goal strategies are explored and how HER interacts with reward shaping. More importantly, I propose a new technique Hindsight Prioritized Experience Replay (HPER) which combines HER with Prioritized Experience Replay (PER)to prioritize which transitions to replay from the buffer based on their expected learning progress. 

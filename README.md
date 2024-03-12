# Learning-from-Failure-or-and-when-surprised
HPER: A new Replay Buffer Algorithm combining HindSight Experience Replay(HER) and Prioritized Experience Replay(PER).

This repo reproduces the results of HindSight Experience Replay(HER) in a single-goal RL setting using the Mountain Car environment. Different goal strategies are explored and how HER interacts with reward shaping. More importantly, I propose a new technique Hindsight Prioritized Experience Replay(HPER) which combines HER with Prioritized Experience Replay(PER) to prioritize which transitions to replay from the buffer based on their expected learning progress. 

Read more about it here: [HPER Report](https://github.com/gourabdey96/Learning-from-Failure-or-and-when-surprised/blob/main/HPER_Report.pdf)

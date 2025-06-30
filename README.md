# pirate-intelligent-agent

What code were you given? What code did you create yourself?
On this project I started with the provided skeleton: the TreasureMaze environment, the GameExperience replay buffer, and a bare‐bones Jupyter notebook with a big “​# TODO: Complete the Q-Training Algorithm Code Block” waiting for my pirate-taming magic. I wrote only the Q-learning loop inside that cell. In that block I created the starting positions, ε-greedy action selection, experience replay sampling, Bellman-error updates via model.train_on_batch, rolling win-rate checks, and early stopping once the buccaneer hit 100% wins.

What do computer scientists do and why does it matter? How do I approach a problem as a computer scientist?
Computer science is a challenging and puzzle solving area. We take a messy, real world problem, and translate it into precise data structures, algorithms, and models that a machine can execute millions of times. It matters because every system from in todays world run with the same principles: formalizing the unknown, breaking into solvable chuncks, then iterating towards correctness and efficiency. My approach mirrored that, I read the specs, wrote out pseudocode, verified methods, built the loop and tested the until it ran flawlessly.

What are my ethical responsibilities to the end user and the organization?
Ethics aren't an afterthough, they are integrated into every line of code. As a computer scientist, we owe it to our users and organizations to build systems that are transparent, respectful of privacy, and robust abainst abuse. I made sure not to hard code any defaults to parameterize exploration so agents dont go off the grid and document each decision clearly.

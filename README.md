# product-stock-simulation-random-walks
This repository contains a Python file with 7 scripts that progressively simulate product stock depletion using random walks.
The project demonstrates step-by-step evolution from simple random walks to multi-product stock simulations, including visualization.

01_basic_random_walk – Implements a simple random walk where a particle can either move left or right with 50% probability on each direction.
02_basic_random_walk_v2-Implements a simple random walk where a particle can either move left OR right with USER defined probabilities on each direction.
03_basic_random_walk_v3-Implements a simple random walk where a particle can either move left OR right OR stay in the same position with USER defined probabilities.
04_multiple_random_walks-Here I simulate 5 identical random walks similar to the first script at the same time.
05_multiple_random_walks-Here I simulate 5 identical random walks with user defined probabilities and custom starting position which apply to all 5 random walks. Particle can move left, right or stay in the same position.
06_multiple_random_walks- particle can move left, right, stay in the same position and in EACH walk the user can set diffrent starting point and probalities
07_product_stock_model- It is massively based on 06 and there has been added a limitation for the random walk to stop when stocks reaches 0.

The final script can be used as a simulation for multiple products stock, where each random walk correspond to each product, steps correspond to minutes/hours/days and the user can set diffrent probabilities to diffrent products.

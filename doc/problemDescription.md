# Optimization problem description

This file contains the description of the projects main problem in a
mathematical fashion.

## Decision variables

The decision variables $N_p \in \mathbb{N}^{(D \times P)}$ are the number of items of a product in a specific advent
calendar door/bag. E.g.

$$N_p[1]["Happy Hippo"] = 0$$

would mean 0 Happy hippos are placed in door 1. This decision variable has size
$D \times P$ where $D$ is the number of doors $24$ and $P$ is the number of
products $P$. 

## Objective function

For now the objective function is the coverage of the advent calendar of the
product set. So e.g. if a calendar uses 4 products out of 5 its coverage is
80%. The project should maximize this number. 


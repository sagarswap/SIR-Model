This project aims to mimic the simulation of one of the most cited papers in Network Science. [Collective dynamics of ‘small-world’ networks](https://www.nature.com/articles/30918) by Duncan J. Watts and Steven H. Strogatz.

# Abstract

Networks of coupled dynamical systems have been used to model biological oscillators Josephson junction arrays excitable media, neural networks, spatial games, genetic control networks and many other self-organizing systems. Ordinarily, the connection topology is assumed to be either completely regular or completely random. But many biological, technological and social networks lie somewhere between these two extremes. Here we explore simple models of networks that can be tuned through this middle ground: regular networks ‘rewired’ to introduce increasing amounts of disorder. We find that these systems can be highly clustered, like regular lattices, yet have small characteristic path lengths, like random graphs. We call them ‘small-world’ networks, by analogy with the small-world phenomenon (popularly known as six degrees of separation15). The neural network of the worm Caenorhabditis elegans, the power grid of the western United States, and the collaboration graph of film actors are shown to be small-world networks. Models of dynamical systems with small-world coupling display enhanced signal-propagation speed, computational power, and synchronizability. In particular, infectious diseases spread more easily in small-world networks than in regular lattices.

# Algorithm

At time t 1⁄4 0, a single infective individual is introduced
into an otherwise healthy population. Infective individuals are
removed permanently (by immunity or death) after a period of
sickness that lasts one unit of dimensionless time. During this time,
each infective individual can infect each of its healthy neighbours
with probability r. On subsequent time steps, the disease spreads
along the edges of the graph until it either infects the entire
population, or it dies out, having infected some fraction of the
population in the process.

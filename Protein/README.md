# Protein
This dataset describes interactions between 230 different proteins. The interaction is encoded as a 1 if two proteins do bind and as a 0 if they do not.

## Origin
The data was first described in a paper by [Hoff (2007)](https://proceedings.neurips.cc/paper/2007/hash/766ebcd59621e305170616ba3d3dac32-Abstract.html). The authors sourced the data from a publication by [Butland et al.](https://doi.org/10.1038/nature03239) in which they showcased a method to detect interacting proteins. They published the interaction data as a pdf supplement, which likely was the basis for the network used by Hoff. Hoff selected the largest connected component of the graph, which includes 230 proteins.

The current version of the dataset called [Protein.csv](./Protein.csv) has been found on the website of James Robert Lloyd, embedded in the [source code](https://jamesrobertlloyd.com/assets/BasicRFM.tar.gz) for a publication by [Lloyd et al. (2012)](https://proceedings.neurips.cc/paper/2012/hash/df6c9756b2334cc5008c115486124bfe-Abstract.html)

## Appearance in Literature
The dataset was mentioned in the following publications (non-exhaustive):
|Author|Date|Title|Link|
|---|---|---|---|
|Hoff|2007|Modeling homophily and stochastic equivalence in symmetric relational data|[link](https://proceedings.neurips.cc/paper/2007/hash/766ebcd59621e305170616ba3d3dac32-Abstract.html)|
|Lloyd, Orbanz, Ghahramani & Roy|2012|Random function priors for exchangeable arrays with applications to graphs and relational data|[link](https://proceedings.neurips.cc/paper/2012/hash/df6c9756b2334cc5008c115486124bfe-Abstract.html)|
|Bloem-Reddy, Orbanz|2018|Random-walk models of network formation and sequential Monte Carlo methods for graphs|[link](https://doi.org/10.1111/rssb.12289)|
|Xu, Liu, Zhe, Bai, Wang & Neville|2019|Variational Random Function Model for Network Modeling|[link](https://doi.org/10.1109/TNNLS.2018.2837667)|



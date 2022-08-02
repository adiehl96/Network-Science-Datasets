# HighSchool
The data in the HighSchool dataset describes the friendships between 90 12th graders. The friendships are encoded as a 1 if they are present and as a 0 if they are not present.

## Origin
The data was first described in a paper by [Hoff (2007)](https://proceedings.neurips.cc/paper/2007/hash/766ebcd59621e305170616ba3d3dac32-Abstract.html). In this paper, the authors have sourced the data from the "National Longitudinal Study of Adolescent Health", which includes information of close friendship ties between study participants. The authors mention a number of 247 participants, while the [official](https://doi.org/10.15139/S3/11900) number of participants in the study is approximately 6500. Hoff did not mention how he subsampled the data. Furthermore, Lloyd et al. published the dataset with only 90 vertices, without further explanation of the subsampling approach.

The current version of the dataset called [HighSchool.csv](./HighSchool.csv) has been found on the website of James Robert Lloyd, embedded in the [source code](https://jamesrobertlloyd.com/assets/BasicRFM.tar.gz) for a publication by [Lloyd et al. (2012)](https://proceedings.neurips.cc/paper/2012/hash/df6c9756b2334cc5008c115486124bfe-Abstract.html)

An older version of the same dataset has been found in the R package "eigenmodel" that Peter Hoff has kept up to date. The column and row names seem to indicate the indices of the subjects befor subsampling, but again no further information is given on how this process took place. The eigenmodel package can be found on [cran](https://cran.r-project.org/web/packages/eigenmodel/index.html) and a backup of one such version can be found on Peter Hoffs [github](https://github.com/pdhoff/eigenmodel/blob/master/data/YX_Friend.rda). 

## Note!
The name used for this network has been changed from HighSchool to Friendship in at least one publication.
## Appearance in Literature
The dataset was mentioned in the following publications (non-exhaustive):
|Author|Date|Title|Link|
|---|---|---|---|
|Hoff|2007|Modeling homophily and stochastic equivalence in symmetric relational data|[link](https://proceedings.neurips.cc/paper/2007/hash/766ebcd59621e305170616ba3d3dac32-Abstract.html)|
|Lloyd, Orbanz, Ghahramani & Roy|2012|Random function priors for exchangeable arrays with applications to graphs and relational data|[link](https://proceedings.neurips.cc/paper/2012/hash/df6c9756b2334cc5008c115486124bfe-Abstract.html)|
|Xu, Liu, Zhe, Bai, Wang & Neville|2019|Variational Random Function Model for Network Modeling|[link](https://doi.org/10.1109/TNNLS.2018.2837667)|

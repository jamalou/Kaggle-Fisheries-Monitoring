# Kaggle-Fisheries-Monitoring
A solution to the [The Nature Conservancy Fisheries Monitoring](https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring) kaggle challenge.
### About
To solve the problem I finetuned some of the top layers of InceptionResnetV2 (trained initially on ImageNet dataset). The solution has about 0.96 log loss on the public leaderboard.

### How to use
Download the challenge's data and put it in the project folder, then run all the cells of the notebook.

### Dependencies
To run this notebook, the packages you need to have are:
* Tensorflow
* Keras
* Pillow
* Pandas

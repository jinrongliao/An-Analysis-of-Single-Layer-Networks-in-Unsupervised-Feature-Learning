### Single Layer neural network  
Single Layer neural network's performence is not so good.  
Which have accuracy of 55% on CIFAR-10  
However, with PCAwhintening and Kmeans, it can reach 75% on CIFAR-10  
[Detailed report in here](https://github.com/yihui-he/Single-Layer-neural-network-with-PCAwhitening-Kmeans/blob/master/report/mp1_Yihui%20He.pdf)  
reference:  
["Analysis Single Layer Unsupervised Feature Learning"](http://ai.stanford.edu/~ang/papers/nipsdlufl10-AnalysisSingleLayerUnsupervisedFeatureLearning.pdf)  
#### How to run  
1. Put cifar-10 dataset in ./dataset
2. run python redo.py dataset

#### files
neural_net.py implement the neural net  
redo.py implement preprocessing  

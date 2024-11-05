# IPR_PROJECT_1_IMPLEMENTATION
The repository consists of 6 ipynb files namely ShanghaiTech_partA, ShanghaiTech_partB, UCF-CC-50, ShanghaiTech_partA-new, ShanghaiTech_partB-new, and UCF-CC-50-new. The first 3 files have been made to reproduce the results of -Crowd Counting with Deep Negative Correlation Learning paper using D-convNet-1 model has been implemented using the details given in the paper.
The other 3 new files have been made to improve the results of the previous implementations using a multi-scale attention mechanism.
Results of the implementation are produced using the Kaggle GPU.
The model architecture is the same in both ShanghaiTech and UCF-CC-50 files, however since the UCF-CC_50 dataset does not have training and testing parts separately, 5-fold cross-validation has been used for the model
evaluation as mentioned in the paper.
To run the files, change the input paths in the dataset loader lines.

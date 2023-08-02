# PreDOMNet

There are Two zip files: "BFGS_ANN_node16_hidden20_xavier" and "BFGS_PreDOMNet_node16_hidden20_pt1000_xavier"

1) "BFGS_ANN_node16_hidden20_xavier" implements the ANN method with BFGS optimizer in 16 nodes and 20 hidden units, training for 15,000 epochs.
2) "BFGS_ANN_node16_hidden20_xavier" implements the PreDOMNet with BFGS optimizer in 16 nodes and 20 hidden units, training for 15,000 epochs with 1,000 epochs of pretraining.
3) Both of Them, "result_multigrid_BFGS_2D.m" file is the main file to configure the hyper-parameters.
4) These example code files makes the implementation developed in the paper "Shin, B.-C., Seo, J.-K.: Neural Networks' Inertia in Dropout-based Pretraining method for Elliptic Boundary Value PDEs on Multigrid Domains".

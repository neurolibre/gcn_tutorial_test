neurolibre : [![Binder](http://binder-wksh2.conp.cloud/badge_logo.svg)](http://binder-wksh2.conp.cloud/v2/gh/zhangyu2ustc/gcn_tutorial_test/master?filepath=notebooks%2F)
public binder : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zhangyu2ustc/gcn_tutorial_test/master?filepath=notebooks%2F)

# GCN_tutorial
this tutorial covers the basics of graph laplacian and graph convolutional networks and how to apply these tools to neuroimging data

## Introduction
Brain graphs provide a relatively simple way of modeling the human brain connectome, by associating nodes with brain regions, and defining edges via anatomical or functional connections. 

Based on this architecture, a non-linear embedding tool, called graph Laplacian, can be used to project the high dimensional brain activities onto subspaces of the graph Laplacian eigenbasis.
This method has gained more and more attention in neuroscience studies, for instance identifying functional areas and networks, generating connectivity gradients and harmonics, and even predicting atrophy patterns of dementia. 

Recently, graph convolutional networks (GCN) was proposed, which combines the graph Laplacian theory with deep learning architectures by extending convolution operations onto the graph domain. 
This approach has shown some promising findings in neuroscience applications, for instance parcellating brain areas and detecting alterations in AD and Autism. 
In our recent study, we applied GCN to annotate the spatiotemporal dynamics of brain dynamics of human cognitive functions using a short series of fMRI volumes. 
I will use this as a case study to illustrate how to apply GCN to brain imaging.
## References
<a id="1">[1]</a> Zhang, Yu, and Pierre Bellec. "Functional Decoding using Convolutional Networks on Brain Graphs." 2019 Conference on Cognitive Computational Neuroscience, Berlin, Germany [PDF](https://ccneuro.org/2019/proceedings/0001137.pdf)

## Code
```notebooks``` includes all the functions and modules you need for this tutorial
```notebooks/Tutorials_GCN_practice2_graph-Laplacian_GCN.ipynb``` the main notebook
```notebooks/model.py``` contains the model definition, including fully-connected, 1stGCN and ChebyNet
```notebooks/utils.py``` contains helpful functions

## Setup
### Prepare the environment
 You could either clone the git-repo or directly using the enviorment prebuild through binder
    open a terminal and type:
```
git clone https://github.com/zhangyu2ustc/gcn_tutorial_test.git
``` 

 Or Click the link to [binder](https://mybinder.org/v2/gh/zhangyu2ustc/gcn_tutorial_test/master?filepath=notebooks%2F) in your browser


### Check the notebook 
 Go to notebook folder and find the .ipynb [notebook](https://github.com/zhangyu2ustc/gcn_tutorial_test/blob/master/notebooks/Tutorials_GCN_practice2_graph-Laplacian_GCN.ipynb)

 Note: It could take a while for the binder to build the enviornment (around 5 minutes). Be patient !  


### check the presentation slides here: [GCN_tutorial_slides](https://drive.google.com/file/d/1Gu28WcHXlwjXQSSmqZZwIcESHff_j-J4/view?usp=sharing)


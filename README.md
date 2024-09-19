# Advanced Topics in Chemical Physics: Introduction to Machine Learning 

This repository contains five lectures and three workshop sessions on introducing machine learning concepts in the advanced physical chemistry module at UoE. 

## Authors
Dr Antonia Mey -- antonia.mey@ed.ac.uk.  
Dr Matteo Degiacomi -- matteo.t.degiacomi@durham.ac.uk

Jasmin Güven, Rohan Gorantla, Ryan Zhu

### Demonstrators 24-25:
Ryan Zhu and Dominic Philips



## Workshop Notebooks

| Workshop               | Materials |
|-----------|-------------------------|
|**Workshop 01: Clustering and Regression**||
|1. Clustering|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_01/01_clustering.ipynb) |
|2. Regression|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_01/02_regression.ipynb) |
|3. Application|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_01/03_application.ipynb) |
|**Workshop 02: Dimensionality Reduction and Classification**||
|1. Dimensionality reduction|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_02/01_dimensionality_reduction.ipynb) |
|2. Classification|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_02/02_classification.ipynb) |
|**Workshop 03:  Deep Learning for Solubility Classification**||
|1. Intro to Pytorch|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_03/01_Intro_to_pytorch.ipynb) |
|2. Solubility classification|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP-ML-workshop/blob/main/Workshops/workshop_03/02_Solubility_classification.ipynb) |

## Local installation

1. Install [anaconda](https://www.anaconda.com/products/distribution).
2. Create a new environment:

   `conda create -n ml_chem`
   
3. Activate the environment:

   `conda activate ml_chem`
   
4. Install [mamba](https://anaconda.org/conda-forge/mamba) to make the installation of packages faster.

   `conda install -c conda-forge mamba`
   
5. Install all the required packages with mamba:

   `mamba install -c conda-forge scikit-learn matplotlib pandas`

For Unit_03 you will also need to install

`mamba install -c conda-forge rdkit seaborn`

and

` mamba install pytorch torchvision torchinfo -c pytorch`

## Project

Release: week 4
Report Deadline: TBC  
Weight: 20%

## Summary of Lectures
### Lecture 1:
- What is machine learning?
- Examples of machine learning (in Chemistry)
- Linear Regressions
- Introduction to unsupervised learning: 	- Clustering (k-means and others)


### Lecture 2:
- Chemistry data is high dimensional
- Dimensionality reduction:
	- Principle component analysis (PCA)
	- Time lagged component analysis (tICA)
	- t-stochastic neighbour embedding (t-SNE) 

### Lecture 3:
- Classification problems
- Classifications in practice:
	- Random Forests	
	- Support vector machine

### Lecture 4:
- Shallow Learning 
- Deep Learning part I
	- Multilayer perceptron 


### Lecture 5:
- Deep Learning Part II
	- Transformers
	- Graph Neural Networks  

## Learning Outcomes
- Understand the main pillars of machine learning
- Know about different clustering techniques as part of unsupervised learning
- Be able to use common nomenclature used in machine learning
- Use Principle component analysis to reduce the dimensions of a data set
- Understand how a regression problem can be cast as a machine learning problem 
- Be aware of how random forests and multilayer perceptrons can be used in a classification problem



## Additional Resources
A handout with additional resources can be found [here.](https://github.com/meyresearch/ML_for_chemistry/blob/main/Handout.pdf)

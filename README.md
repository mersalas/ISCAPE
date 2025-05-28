# ISCAPE
ISCAPE: **I**nterpretable **S**upport vector **C**lassifier of **A**ntibacterial activity of **P**eptides against **_E_**_scherichia coli_

Paper: [Interpretable support vector classifier for reliable prediction of antibacterial activities of modified peptides against *Escherichia coli*]()

![Graphical abstract]()

## Dependencies: 

Packages required to run the notebooks:
- [Python 3.8](https://www.python.org/downloads/release/python-380/)
- [pyforest 1.1.0](https://github.com/8080labs/pyforest)
- [umap-learn 0.5.6](https://github.com/lmcinnes/umap)
- [scikit-optimize 0.10.1](https://github.com/scikit-optimize/scikit-optimize)
- [xgboost 1.7.6](https://github.com/dmlc/xgboost/tree/master)
- [lightgbm 4.0.0](https://github.com/microsoft/LightGBM)
- [deepchem 2.7.1](https://github.com/deepchem/deepchem)
- [deep-forest 0.1.7](https://github.com/LAMDA-NJU/Deep-Forest)
- [shap 0.42.1](https://github.com/shap/shap/tree/master) 

## Colab notebooks:

- [algo_search](https://github.com/mersalas/ISCAPE/blob/main/algo_search.ipynb): contain the codes used in the model development
- [models_pred](https://github.com/mersalas/ISCAPE/blob/main/models_pred.ipynb): shows the predictions of all models on our own short peptide dataset 
- [ISCAPE](https://github.com/mersalas/ISCAPE/blob/main/ISCAPE.ipynb): codes for ISCAPE model; data can be replaced with your own data to make peptide activity prediction and important feature identification

## How to cite:
```bibtex
@unpublished{Salas2025,
author = {Salas, Remmer and Sabido, Portia Mahal G. and Nellas, Ricky},
journal = {},
doi = {},
title = {{Interpretable support vector classifier for reliable prediction of antibacterial activities of modified peptides against *Escherichia coli*}},
url = {},
year = {2025}
}
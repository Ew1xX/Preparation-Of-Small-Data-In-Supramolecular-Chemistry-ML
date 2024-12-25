# Communication: Strategies of Small Datasets Preparation for Machine Learning in Chemistry 
This repository contains code notebooks, figures and datasets used in the research.

## Notebooks
**Notebook №1:** Collecting guests (their SMILES and binding constants with pillar[6]arene (WP6)) from scientific sources for original data (named WP6 Dataset), creating addtional data with guests related to similar to WP6 compounds (named WP6++ Dataset)

**Notebooks №2.1 and №2.2:** Generating molecular descriptors and fingerprints (Morgan, Avalon, Pattern, MACCS, AtomPairs, TopologicalTorsionGenerator), selecting the most imporant features by using CatBoostRegressor. Creating heatmaps for searching the most correlated fingerprints to the target metric. Creation two normalized datasets with top-10 descriptors, top-15 AtomPairs features and binding constants

**Notebooks №3.1 and №3.2:** Building basic machine learning models and evaluating them on two recieved datasets.

**Notebooks №4.1 and №4.2:** Building 5 CTGAN models (by the samenamed library) for generating 5  datasets of synthetic data. Selection of the dataset with the most quantity of  in-bounded values.

**Notebook №5:** Evaluating the synthetic data on similarity with the real datasets. 

**Notebooks №6.1 and №6.2:** Building same machine learning models and evaluating them on various mixtures of real and synthetic data.

## Figures
Fig1 - descriptors selection. (A) for WP6 dataset and (B) for WP6++ dataset. More plot about selection see in the Notebook №1
Fig2 - heatmaps for choosing the best fingerprints.(A) for WP6 dataset and (B) for WP6++ dataset.
Fig3 - metics obtained after evaluating a set of basic models on (A) WP6 dataset and (B) on WP6++ dataset.
Fig4 - comparison generated data based on WP6 and real WP6 data by columns in dataset.
Fig5 - comparison generated data based on WP6++ and real WP6++ data by columns in dataset.
Fig6 - metics obtained after evaluating a set of basic models on (25) WP6 dataset + 25% of generated data dataset, (50) WP6 dataset + 50% of generated data dataset and (60) WP6 dataset + 60% of generated data dataset
Fig7 - metics obtained after evaluating a set of basic models on (25) WP6 dataset + 25% of generated data dataset, (40) WP6 dataset + 40% of generated data dataset and (48) WP6 dataset + 48% of generated data dataset

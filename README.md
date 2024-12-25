# Communication: Strategies of Small Datasets Preparation for Machine Learning in Chemistry 
This repository contains code notebooks, figures and datasets used in the research.

**Notebook №1:** Collecting guests (their SMILES and binding constants with pillar[6]arene (WP6)) from scientific sources for original data (named WP6 Dataset), creating addtional data with guests related to similar to WP6 compounds (named WP6++ Dataset)

**Notebooks №2.1 and №2.2:** Generating molecular descriptors and fingerprints (Morgan, Avalon, Pattern, MACCS, AtomPairs, TopologicalTorsionGenerator), selecting the most imporant features by using CatBoostRegressor. Creating heatmaps for searching the most correlated fingerprints to the target metric. Creation two normalized datasets with top-10 descriptors, top-15 AtomPairs features and binding constants

**Notebooks №3.1 and №3.2:** Building basic machine learning models and evaluating them on two recieved datasets.

**Notebooks №4.1 and №4.2:** Building 5 CTGAN models (by the samenamed library) for generating 5  datasets of synthetic data. Selection of the dataset with the most quantity of  in-bounded values.

**Notebook №5:** Evaluating the synthetic data on similarity with the real datasets. 

**Notebooks №6.1 and №6.2:** Building same machine learning models and evaluating them on various mixtures of real and synthetic data.

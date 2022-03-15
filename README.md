# Data Ingest

This repository provides an exploration of statistical methods for automated data ingest

The notebooks "common_distribution_testing," "scale_testing," and "dsitribution_drift_testing" all explore a variety of statistical tests (Welch's T Test, MDL, KS Testing, KL Divergence, and PSI Testing) for automated column matching with limited information. 

The notebook one_to_many_cat_testing explores an attempt at trying to model 1:many translation between categorical features, where one or more feature values may have been split in the ingest data.

Finally, the notebook automated_ingest_testing follows work I did in using a model-based approach to approximate feature similarity between an existing schema and an ingested dataset. 

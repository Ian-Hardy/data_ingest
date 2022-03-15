# Data Ingest

This repository provides an exploration of statistical methods for automated data ingest

The notebooks "common_distribution_testing," "scale_testing," and "dsitribution_drift_testing" all explore a variety of statistical tests (Welch's T Test, MDL, KS Testing, KL Divergence, and PSI Testing) for automated column matching with limited information. 

The notebook one_to_many_cat_testing explores an attempt at trying to model 1:many translation between categorical features, where one or more feature values may have been split in the ingest data.

Finally, the notebook automated_ingest_testing follows work I did in using a model-based approach to approximate feature similarity between an existing schema and an ingested dataset. 

All of this work was done in Google Colab, so the notebooks have some header cells at the top referencing my colab folders. Feel free to upload to your drive an play around with it, you may need to change the cells there. If you want to run it on your local machine, you can just start at the csv read commands.

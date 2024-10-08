## Updated TimeGAN to use tensorflow2 for testing with wearable data

Main Repository: Codebase for "Time-series Generative Adversarial Networks (TimeGAN)-  (NeurIPS), 2019.
Authors: Jinsung Yoon, Daniel Jarrett, Mihaela van der Schaar
Paper Link: https://papers.nips.cc/paper/8789-time-series-generative-adversarial-networks


This directory contains testing of TimeGAN for synthetic time-series data generation using a real-world dataset from a wearable device.

-   dehydration monitoring data: https://www.mdpi.com/1424-8220/22/5/1887/htm, you can contact the author to get access to the data.

Results are published in the paper: Sabry, F.; Labda, W.; Eltaras, T.; Hamza, F.; Elzoubi, K. and Malluhi, Q. (2023). <a href="https://www.researchgate.net/profile/Farida-Sabry/publication/369015931_Wearable_Data_Generation_Using_Time-Series_Generative_Adversarial_Networks_for_Hydration_Monitoring/links/648ac12a712bd82962233f5c/Wearable-Data-Generation-Using-Time-Series-Generative-Adversarial-Networks-for-Hydration-Monitoring.pdf
">Wearable Data Generation Using Time-Series Generative Adversarial Networks for Hydration Monitoring </a>. In Proceedings of the 16th International Joint Conference on Biomedical Engineering Systems and Technologies - BIOSIGNALS, ISBN 978-989-758-631-6; ISSN 2184-4305, pages 94-105. DOI: 10.5220/0011757200003414

To run the pipeline for training and evaluation on TimeGAN framework, simply run 
python3 -m main_timegan.py or see jupyter-notebook tutorial of TimeGAN in tutorial_timegan.ipynb.
### Further code explanation for TimeGAN can be followed in details on the main TimeGAN repository


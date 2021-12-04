# Exploring Data Augmentation Methods on Social Media Corpora

Authors: Isabel Garcia Pietri, Kineret Stanley 

## Summary

In this project we explore data augmentation techniques in the context of text classification using two social media datasets. We explore popular varieties of data augmentation, starting with oversampling, Easy Data Augmentation (Wei and Zou, 2019) and Back-Translation (Sennrich et al., 2015). We also consider Greyscaling, a relatively unexplored data augmentation technique that seeks to mitigate the intensity of adjectives in examples. Finally, we consider a few-shot learning approach: Pattern-Exploiting Training (PET) (Schick et al., 2020). For the experiments we use a BERT transformer architecture. 


## Files Description

- `notebooks/RtGender-Notebooks/` directory contains the experiments with the RtGender dataset
- `notebooks/TRAC-2-notebooks/` directory contains the experiments with the TRAC-2 dataset
- `papers` directory: related papers
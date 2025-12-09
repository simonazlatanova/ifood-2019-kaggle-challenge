# iFood-2019 CNN Classification - Kaggle 

## Repository Structure

This repository contains two main Jupyter notebooks and associated results:

### Notebooks
- **supervised_part.ipynb**  
  This notebook contains the supervised learning pipeline, where a custom CNN (<5M parameters) is trained end-to-end on the iFood-2019 dataset.

- **self-supervised-part.ipynb**  
  This notebook contains the self-supervised learning pipeline. The same CNN encoder is pretrained using SimCLR, and downstream classifiers are trained on the extracted features.

Together, these notebooks provide a direct comparison between supervised and self-supervised learning using the same architecture and dataset.

### Results
- **results/SL classification report - final model 100 epochs.txt**  
  Contains the classification report for the final supervised model trained for 100 epochs.

- **results/hyperparameter tunning - SL.txt**  
  Contains the results of hyperparameter tuning for the supervised learning pipeline.



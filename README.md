# fmriNet

## Categorization of seen images from brain activity using sequence models

### Arash Jamalian, Rafi Ayub

This repository is for the CS230 project, "Categorization of seen images from brain activity using sequence models". Please see Poster_230.pdf and CS230FinalReport.pdf for an overview of the project.

Notebooks were run on AWS p2.xlarge EC2 instance with 61GiB RAM using conda_tensorflow_p36 enviornment.

Tesnorflow version: 2.0.0

BOLD5000 data set needs to be dowloaded by following instructions in https://bold5000.github.io/download.html.

To run mega_classifier_all.ipynb notebook, you need to get preprocessed ROIs and image names from https://ndownloader.figshare.com/articles/6459449/versions/4 and place it under /home/ubuntu directory.

Description of notebooks:

- mega_classifier_all.ipynb: main project notebook where we label data and develop the LSTM model

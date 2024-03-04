# DS-Project-4
Flatiron School Data Science Project - Phase 4

## Overview
* Purpose: Create a Classifier to determine plant disease
* Source of data: TensorFlow Dataset 'plant_village'
* Data: ~50,000 images, 38 classes divided into 14 crop species and 26 diseases

 
# Presentation and Sources
Presentation: [Link](https://docs.google.com/presentation/d/1MNKhGSry9dcw3o19hOz2Eds7e--Gmn6QKhyBu8HuOcw/edit#slide=id.g9f3cfcb535_0_188)

Images dataset: [Link](https://data.mendeley.com/datasets/tywbtsjrjv/1)

# Repository Navigation
Our Github Repository contains 1  main folder named Notebooks. The other images folder just contains images for this document. The Notebooks folder has 2  notebooks in it. The first of these notebooks is titled Data_Preproccessing and contains all of my data cleaning and preprocessing steps. It is important to run this notebook first as cleaned data files are created which the Modeling notebook then calls. The next notebook is titled Modeling_Analysis and contains all of the models we created as well as evaluation for each model as well.

## Data Analysis & Recommendations
* Able to get ~97% test accuracy using a 4 block Convolutional Neural Network
<img src = '/images/model_CM.png'>

<img src = '/images/metrics.png'>

* VGG model transfer learning model with batch normalization slightly worse
<img src = '/images/transfer_batch_cnn.png'>




Our recommendations are the following:
* Using CNNs to identify plant disease is a viable option
* Features extracted from general images in the vgg model were applicable to this problem







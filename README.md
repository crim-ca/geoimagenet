# GeoImageNet
This repository explains how to use the Mahine Learning API from the [GeoImageNet](https://geoimagenet.ca) platform. The API is composed of two parts:
1. Access to the annotations and the taxonomies: https://geoimagenet.ca/api/v1/redoc
2. A ML API (restricted to registered users only): https://geoimagenet.ca/ml/api#

## Notebooks
A few notebbooks are demonstrating the basic use cases of the platform. They can be executed with Google Colab.
* Packaging of a patch classification model: [classif_model_packaging](https://github.com/crim-ca/geoimagenet/blob/master/classif_model_packaging.ipynb) 
* Packaging of a SegNet model: [seg_model_packaging](https://github.com/crim-ca/geoimagenet/blob/master/seg_model_packaging.ipynb) 
* Use of the annotations: coming soon...

## Documentation

### How to Package Your Model

In order to submit a new model to the platform, the steps are the following:
1. The model must be trained using PyTorch and the parameters saved as a .pth 
2. Add the model code to the [model repository](https://github.com/sfoucher/gin-model-repo) (by creating a fork of the repo)
3. The trained model must be packaged using the [thelper](https://github.com/plstcharles/thelper) framework.

Two notebooks are available showing how to package a [ResNet](https://github.com/crim-ca/geoimagenet/blob/master/classif_model_packaging.ipynb)  and a [UNet](https://github.com/crim-ca/geoimagenet/blob/master/seg_model_packaging.ipynb).

### How to Use the Annotations for Model Training

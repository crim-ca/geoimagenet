
## Welcome to GeoImageNet Project


![Alt text](./img/Capture1.JPG){: width="450px"}

## Creating and Managing Annotations {#annotations}

### Taxonomy Browser {#taxonomy}
The taxonomy browser shows one or two taxonomies as a tree. By clicking on each class you can access any subclasses. Next to each class name is indicated information about the current annotations (the numbers include all the class children). The circled numbers have different meanings depending on the status of the annotations:
- Blank: new annotations
- In light green: annotations released
- Dark green: annotations validated
- Red: annotations rejected
- Black: annotations erased

![Alt text](./img/Capture2.JPG)

The following icons trigger different actions for the corresponding class (and its children):
- ![Alt text](./img/Selection_010.jpg) view the annotations for the corresponding class
- ![Alt text](./img/Selection_011.jpg) select this class (and subclasses) to appear in the workspace
- ![Alt text](./img/Selection_012.jpg) send the new annotations for validation

### Workspace
The workspace shows all the annotations for the classes slected in the taxonomy browser.
![Alt text](./img/Selection_014.jpg)

Several modes are available:
- Navigation mode: the user can click on the thumbnails and quickly navigate to the corresponding location
- Editing mode: the user can edit new annotations only, the vector will appear in blue and a circle will appear along the shape
- Delete mode: the user can delete new annotations by clicking on the shape, a confirmation dalog will then appear.
- Release mode: new annotations will be released for validation
- Validation mode: new annotations that have been released can be validated.

### Datasets {#datasets}
The dataset section allows the user to donwload annotations and training data.

![Alt text](./img/Capture4.JPG){: width="450px"}

Only administrator can create new datasets.



## Managing Models

### Packaging
In order to submit a new model to the platform, the steps are the following:
1. The model must be trained using PyTorch and the parameters saved as a .pth 
2. Add the model code to the [model repository](https://github.com/sfoucher/gin-model-repo) (by creating a fork of the repo)
3. The trained model must be packaged using the [thelper](https://github.com/plstcharles/thelper) framework.

Two notebooks are available showing how to package a [ResNet](https://github.com/crim-ca/geoimagenet/blob/master/classif_model_packaging.ipynb)  and a [UNet](https://github.com/crim-ca/geoimagenet/blob/master/seg_model_packaging.ipynb).

### Pushing Models

## API {#api}

This documentation explains how to use the Machine Learning API from the  platform. The API is composed of two parts:
1. Access to the annotations and the taxonomies: https://geoimagenet.ca/api/v1/redoc
2. A ML API (restricted to registered users only): https://geoimagenet.ca/ml/api#

## Notebooks
A few notebbooks are demonstrating the basic use cases of the platform. They can be executed with Google Colab.
* Packaging of a patch classification model: [classif_model_packaging](https://github.com/crim-ca/geoimagenet/blob/master/classif_model_packaging.ipynb) 
* Packaging of a SegNet model: [seg_model_packaging](https://github.com/crim-ca/geoimagenet/blob/master/seg_model_packaging.ipynb) 
* Use of the annotations: coming soon...

## How to Use the Annotations for Model Training {#header1}
Coming soon...


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

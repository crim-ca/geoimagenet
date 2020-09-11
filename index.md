
## Welcome to GeoImageNet Project


You can use the [editor on GitHub](https://github.com/crim-ca/geoimagenet/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.



## How to Use the Annotations for Model Training {#header1}
Coming soon...

![Alt text](./img/Capture1.JPG)

## Creating and Managing Annotations 


[Link back to header 1](#header1)

## Managing Models

### Packaging

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

## Documentation

### How to Package Your Model

In order to submit a new model to the platform, the steps are the following:
1. The model must be trained using PyTorch and the parameters saved as a .pth 
2. Add the model code to the [model repository](https://github.com/sfoucher/gin-model-repo) (by creating a fork of the repo)
3. The trained model must be packaged using the [thelper](https://github.com/plstcharles/thelper) framework.

Two notebooks are available showing how to package a [ResNet](https://github.com/crim-ca/geoimagenet/blob/master/classif_model_packaging.ipynb)  and a [UNet](https://github.com/crim-ca/geoimagenet/blob/master/seg_model_packaging.ipynb).

## Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/crim-ca/geoimagenet/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

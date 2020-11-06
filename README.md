# Using a Convolutional Neural Network To Detect Pneumonia Using X-Ray Images

**Author**: Vivienne DiFrancesco

The contents of this repository detail an analysis of a convolutional neural network to predict if X-rays show patients with pneumonia or not. This analysis is detailed in hopes of making the work accessible and replicable.


### Business problem:

The purpose of this project is to use a Convolutional Neural Network (CNN) to predict disease status of children's chest X-rays. The prediction is set up as a binary problem with the classes being normal or pneumonia. The hope is that by being able to predict pneumonia or normal using a neural network, it would assist physicians in being able to make more accurate and swift diagnoses to ultimately improve patient outcomes.


### Data
The images used for this project are from the Kaggle website. The images are X-rays of children aged one through five from Guangzhou China taken as part of routine care. The pneumonia cases in this dataset include images for bacterial and viral pneumonia. There are over 5,800 images total in the dataset split into a training, validation, and test set of pneumonia or normal. The X-rays were evaluated by multiple experts to identify each image as normal or pneumonia for accurate classification.

The data can be downloaded from Kaggle here:
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia


## Methods
The approach for this project was to test multiple model parameters and architectures to see how the model changed and to judge performance. Ultimately the goal was to find the most accurate model while also keeping in mind that an inaccurate prediction of classifying a patient as normal when they actually have pneumonia (false negative) would be a worse outcome than classifying a patient as having pneumonia when they actually do not (false positive). 

The data was downloaded and the folder structure broken down to be able to redistribute into more even and better measured splits at the start. A rather basic and shallow CNN model was trained as a baseline. Then various parameters were tested and compared to the baseline. Finally, some parameters were combined to try to achieve optimal performance.

## Results

### Here are examples of how to embed images from your sub-folder


#### Visual 1
![graph1](./images/visual1.png)
> Sentence about visualization.

#### Visual 2
![graph2](./images/visual2.png)
> Sentence about visualization.


## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information
Please review the narrative of our analysis in [our jupyter notebook](./main_notebook.ipynb) or review our [presentation](./SampleProjectSlides.pdf)

For any additional questions, please contact **email, email, email)


##### Repository Structure:

Here is where you would describe the structure of your repoistory and its contents, for exampe:

```

├── README.md                       <- The top-level README for reviewers of this project.
├── main_notebook.ipynb             <- narrative documentation of analysis in jupyter notebook
├── presentation.pdf                <- pdf version of project presentation
└── images
    └── images                          <- both sourced externally and generated from code

```

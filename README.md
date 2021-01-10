# Supervised Learning (Image classifier) 
## using TensorFlow and Keras
This project is part of the CharityML project for [the Udacity course: Intro to Machine Learning with TensorFlow](https://www.udacity.com/course/intro-to-machine-learning-with-tensorflow-nanodegree--nd230), and [its github repository](https://github.com/udacity/intro-to-ml-tensorflow). 

In this project, first  code for an image classifier built with TensorFlow is developed, then it will be converted it into a command line application.

### Goal
Classify images of flowers to 102 diffrent categories.


### Data
A [dataset](https://www.tensorflow.org/datasets/catalog/oxford_flowers102) from Oxford of 102 flower categories is used. This dataset has 1,020 images in the training and avaluation set, and 6,149 images in the test set.

## Pretarined model
A [MobileNet pre-trained network](https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4) from TensorFlow Hub is used.
The model is used without its last layer, and some fully connected layers with dropout is added sequentially to be trained on the data. 
### Code

The code is provided in the `finding_donors.ipynb` notebook file. the `visuals.py` Python file and the `census.csv` dataset file is used. 

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Pipeline 
My pipeline consist of the follwoing steps, and the code is called `finding_donors.ipynb`. I used the following libraries

1. Importing data
```

```
2. Exploring the data, e.g. computing the number records for each output class 
```

```

3. Preprocessing the data

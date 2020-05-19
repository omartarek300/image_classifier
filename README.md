# Intro to Machine Learning - TensorFlow Project

Project code for Udacity's Intro to Machine Learning with TensorFlow Nanodegree program. In this project, you will first develop code for an image classifier built with TensorFlow, then you will convert it into a command line application.

In order to complete this project, you will need to use the GPU enabled workspaces within the classroom.  The files are all available here for your convenience, but running on your local CPU will likely not work well.

You should also only enable the GPU when you need it. If you are not using the GPU, please disable it so you do not run out of time!

The notebook utilizes [MobileNetV2](https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4) feature extractor as the base model to classify novel flower images.

## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [TensorFlow](http://tensorflow.org)
- [TensorFlow Hub](https://www.tensorflow.org/hub)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Files
- `Project_Image_Classifier_Project.ipynb`: This is the main notebook to create and train a TensorFlow Keras model to predict the type of a flower from its image.
- `Project_Image_Classifier_Project.html`: HTML format of the notebook for viewing in browser
- `predict.py`: The command line application that implements the trained deep learning network to classify an input flower image.
- `my_model.h5`: The final deep learning model that predicts the flower type from its image with above 90% accuracy.
- `label_map.json`: The mapping of the key values to their corresponding flower types.
- `workspace-utils.py`: The supporting methods to keep the notebook active during long deep learning training phase.

## Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook Project_Image_Classifier_Project.ipynb
```  
or
```bash
jupyter notebook Project_Image_Classifier_Project.ipynb
```

This will open the iPython Notebook software and project file in your browser.

**Important Notice**: The deep learning network for this project is *very* deep and dense. Thus, running this notebook might require GPU to be enabled.

## Data

The data for this project is quite large - in fact, it is so large you cannot upload it onto Github.  If you would like the data for this project, you will want download it from the workspace in the classroom.  Though actually completing the project is likely not possible on your local unless you have a GPU.  You will be training using 102 different types of flowers, where there ~20 images per flower to train on.  Then you will use your trained classifier to see if you can predict the type for new images of the flowers.



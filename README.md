
# Object Classification

Object localization is defined as a CNN, classifying a single object among several classes.

Content:
- DogsVsCats.ipynb contains code for classifying a single animal (dog or cat) in an image.
- predict.ipynb contains code for predicting any image for a cat or dog.
- CNN_model.h5 is an internal database for storing the weight values of the trained CNN.

### Packages:
- Jupyter-Notebook (Python)
- keras

### Instructions:

- Download DogsVsCats.ipynb.ipynb
- Download predict.ipynb
- either download CNN_model.h5 to spare training and predict any cat or dog image with predict.ipynb
- or download dataset: the source of the image datasets: https://www.kaggle.com/
- Make sure to edit the pwd for the data(sub)sets
- Run code



# Object Localization

Object localization is defined as a CNN, classifying a single object among several classes and drawing a single bounding box around that object.

Content:
- Dogs_vs_Cats_Localization_functional.ipynb contains code for classifying a single animal (dog or cat) in an image and drawing a bouding box around it.

### Packages:
- Jupyter-Notebook (Python)
- numpy
- PIL
- tensorflow
- keras
- matplotlib
- xml

### Instructions:

- Download Dogs_vs_Cats_Localization_functional.ipynb 
- Download dataset: the source of the image datasets: https://www.robots.ox.ac.uk/~vgg/data/pets/
**Caution**: I noticed, images and labels might be corrupted in its chronology!
- Make sure to edit the pwd for the data(sub)sets
- Run code 

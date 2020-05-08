
# Object Classification

Object localization is defined as a CNN, classifying a single object among several classes.

### Content:
- DogsVsCats.ipynb contains code for classifying a single animal (dog or cat) in an image.
- predict.ipynb contains code for predicting any image for a cat or dog.
- CNN_model.h5 is an internal database for storing the weight values of the trained CNN.

### Packages:
- Jupyter-Notebook (Python)
- keras

### Instructions:

1. Download DogsVsCats.ipynb.ipynb
2. Download predict.ipynb
3. either download CNN_model.h5 to spare training and predict any cat or dog image with predict.ipynb
 **or** download dataset for own training. The source of the image datasets: https://www.kaggle.com/
4. Make sure to edit the pwd for the data(sub)sets
5. Run code



# Object Localization

Object localization is defined as a CNN, classifying a single object among several classes and drawing a single bounding box around that object.

### Content:
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

1. Download Dogs_vs_Cats_Localization_functional.ipynb 
2. Download dataset. The source of the image datasets: https://www.robots.ox.ac.uk/~vgg/data/pets/
**Caution**: I noticed, images and labels might be corrupted in its chronology!
3. Make sure to edit the pwd for the data(sub)sets
4. Run code 

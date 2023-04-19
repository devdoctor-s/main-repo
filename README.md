# official website
[![Deploy Jekyll with GitHub Pages dependencies preinstalled](https://github.com/devdoctor-s/main-repo/actions/workflows/jekyll-gh-pages.yml/badge.svg)](https://github.com/devdoctor-s/main-repo/actions/workflows/jekyll-gh-pages.yml)
# https://www.tensorflow.org/tutorials/keras/basic_classification 

import tensorflow as tf
from tensorflow import keras


fashion_mnist = keras.datasets.fashion_mnist


(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()


class_names = ['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat',
  'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']
  
  
  

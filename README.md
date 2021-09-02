# Food_101
It is a project which classifies food images. Dataset is given from https://www.tensorflow.org/datasets/catalog/food101

It consists of 101 classes and 101000 images. It is used Tensorflow dataset(TFDS).

For traing the model, it is utilized transfer learning (using a pretrained EfficientNetB0) and then fine tune it.

For training the model is used Mixed Precision which reduces the training time and memory requirments, so that the performance of model is not affected.

At the time of doing this project tensorflow==2.4.1 was compatible with Mixed Percision.  

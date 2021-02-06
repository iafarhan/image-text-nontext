# image-text-nontext
# image-text-nontext
This is an implementation of **predict whether an image has TEXT or NOT?** challenge on kaggle.
I took the dataset from this link : https://www.kaggle.com/c/padhai-module1-level-1.


**About Dataset** : The goal is to identify the presence of a character in images.  The character images are compiled in Tamil, Hindi and English.


The implementation is done in **pytorch**. Pytorch's sequential API is used to build a classifier with cross entropy loss. you can find the model in the notebook. Sort of negative samping is done to ensure that model generalizes and knows about backgrounds as well.


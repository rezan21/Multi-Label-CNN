# Multi-Label-CNN
Multi-Label Classification of RGB Images via Convolutional Neural Networks


### Multi-Class vs Multi-Label
> **Multi-class classification:** There are more than two classes and every observation belongs to one and only one class. e.g: An ecommerce company wants to categorize products like smartphones based on their brands (Samsung, Huawei, Apple, Xiaomi, Sony or Other).

> **Multi-label classification:** There are two classes or more and every observation belongs to one or multiple classes at the same time. Example of application is medical diagnosis where we need to prescribe one or many treatments to a patient based on his signs and symptoms.
[reference](https://towardsdatascience.com/multi-label-image-classification-in-tensorflow-2-0-7d4cf8a4bc72 "reference")


### Convolutional Neural Network (CNN)
> The Convolutional Neural Network gained popularity through its use with image data, and is currently the state of the art for detecting what an image is, or what is contained in the image.
The basic CNN structure is as follows: Convolution -> Pooling -> Convolution -> Pooling -> Fully Connected Layer -> Output

> Convolution is the act of taking the original data, and creating feature maps from it.Pooling is down-sampling, most often in the form of "max-pooling," where we select a region, and then take the maximum value in that region, and that becomes the new value for the entire region. [reference](https://pythonprogramming.net/convolutional-neural-network-deep-learning-python-tensorflow-keras/ "reference")


### Dataset
This repo only contains a limited number of images. Full dataset of 20,000 images of cats and dogs is available at: [Microsoft Cats & Dogs Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54765).


### Used Libraries:
- Tensorflow (GPU)
- OpenCV
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib

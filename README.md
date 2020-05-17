# Face Features Recognition using Fastai


1. The Jupyter notebook displays the use of Fastai on CelebA dataset (https://www.kaggle.com/jessicali9530/celeba-dataset)
2. It identifies characteristics of a face both in group && solo images


Model Details:

1. Used HAAR filters in OpenCV to first identify & crop images for training model
2. Used Resnet50 pretrained model in fastai to train on these cropped images
3. For prediction mechanism first in an image the face coordinates are identified & then on these the predictions of labels are performed

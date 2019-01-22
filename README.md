# Neural-Style-Transfer
Neural style transfer is a technique used to generate images in the style of another image. The neural-style algorithm takes a content-image as input, a style image, and returns the content image as if it were painted using the artistic style of the style image.

# Transfer Learning
[Transfer learning](https://en.wikipedia.org/wiki/Transfer_learning) is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.[1] For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks. This area of research bears some relation to the long history of psychological literature on transfer of learning, although formal ties between the two fields are limited.

```We apply transfer learning by using the pretrained VGG19 model which was already trained on Imagenet Dataset to extract the features of both the content and style images```

# Requirements
1. PyTorch
2. Numpy
3. PIL

```This is the implementation of the [original paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)```

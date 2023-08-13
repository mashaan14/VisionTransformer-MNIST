# VisionTransformer-MNIST

## An attention map for a test image ([code](https://github.com/mashaan14/VisionTransformer-MNIST/blob/main/VisionTransformer_MNIST.ipynb))
This notebook is designed to plot the attention maps of a vision transformer trained on MNIST digits. Looking at the attached gif, the neural net knows where to “pay attention”.

I’ve looked at multiple resources, but these two were particularly useful:
  - https://lightning.ai/docs/pytorch/stable/notebooks/course_UvA-DL/11-vision-transformer.html
  - https://medium.com/@hirotoschwert/an-unofficial-colab-walkthrough-of-vision-transformer-8bcd592ba26a

<p align="center">
  <img src="myimage.gif" />
</p>

## An attention map for query and test images ([code](https://github.com/mashaan14/VisionTransformer-MNIST/blob/main/VisionTransformer_MNIST_query_key.ipynb))
Given query and key images, the code here will plot an attention map. I used MNIST digits dataset.

I borrowed the transformer code from this link:
  - https://lightning.ai/docs/pytorch/stable/notebooks/course_UvA-DL/11-vision-transformer.html

<p align="center">
  <img src="myimage.gif" />
</p>


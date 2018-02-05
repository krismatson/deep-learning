## Transfer Learning
In this lesson we'll be learning about transfer learning. In practice, you won't typically be training your own huge networks. There are multiple models out there that have been trained for weeks on huge datasets like [ImageNet](http://www.image-net.org/). In this lesson, you'll be using one of these pretrained networks, [VGGNet](http://www.robots.ox.ac.uk/~vgg/research/very_deep/), to classify images of flowers.

We'll be using a pretrained network from https://github.com/machrisaa/tensorflow-vgg. Make sure you clone this repository into the transfer-learning directory if it is empty to start. 
```
cd  transfer-learning
git clone https://github.com/machrisaa/tensorflow-vgg.git tensorflow_vgg
```
### Additional Packages
To run this code, you'll need a few packages you might not have installed in your environment. You'll need all the normal ones, plus tqdm and scikit-image. To install them, use Conda as usual:
```
pip install tqdm
conda install scikit-image
```

# Using pix2pix to give color to the flowers in grayscale
I have made this program using the algorithm pix2pix. This program converts images from grayscale to color.

## Why flowers?
I tried with all kind of images but it is to difficult and it would need a lot of images and several days to train my model. Then I tried it with images of a specific subject, images of flowers.

The model have been trained using images of flowers from: http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html

## Converting images to grayscale
To train my model I needed the real images and the images in grayscale.
I used a very simple program to transform the [images to grayscale](/images%20to%20grayscale.ipynb).
With this I have 8189 color images and 8189 images in grayscale and this is my dataset.

## Motivation
To implement this pix2pix algorithm I have based on [the explanation on tensorflow](https://www.tensorflow.org/beta/tutorials/generative/pix2pix) and the [youtube video of Dot CSV](https://youtu.be/YsrMGcgfETY). I want to participate in the challenge [#RetoDotCSV2080Super](https://www.youtube.com/watch?v=BNgAaCK920E).



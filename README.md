# MNIST

Jupyter notebooks are great! They help you execute parts of code and see the output right there. Great method for data exploration and making inferences thereof. Especially useful in machine learning.

Here, I've written hard coded K Nearest Neighbour Algorithm instead of using the sklearn pre defined function. It's much slower but does the job and really helped me learn the why and how this algorithm works.

The dataset is of handwritten digits in the form of 28x28 sized images. 
https://en.wikipedia.org/wiki/MNIST_database

There are 60,000 images in the dataset. I've done a 42000/28000 train-test split.
The algorithms takes a humungous amount of time to run(8 hours in this case) when trained on the entire 42000 images and predicting all 28000 images.

The accuracy I got wasn't too bad even when compared to the state of the art algorithms, so I'm a happy man.

# Case study : Fashion Class Classification 

## Description
The global fashion industry is valued at three trillion dollars and accounts for two percent of the world's GDP. The fashion industry is undergoing a dramatic transformation by adopting new computer vision and machine learning and deep learning techniques. In this case study, we will look at a hypothetical situation, will assume that a fashion retailer hired you to build a virtual stylist assistant that looks at customer Instagram and Facebook images and classifies what fashion category they are wearing, either bags, dresses and pants. The virtual assistant can help the retailer detect and forecast fashion trends and launch targeted marketing campaigns. in this study, we're going to use the fashion MNIST data. It's a dataset that contains images of bags, shoes and dresses and we're asking the deep network to classify the images into ten classes.

Fashion-MNIST is a dataset of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes

## Content 

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

## Labels 

Remember the 10 classes decoding is as follows:
* 0 => T-shirt/top
* 1 => Trouser
* 2 => Pullover
* 3 => Dress
* 4 => Coat
* 5 => Sandal
* 6 => Shirt
* 7 => Sneaker
* 8 => Bag
* 9 => Ankle boot

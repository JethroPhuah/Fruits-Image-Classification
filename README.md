# Fruits-Image-Classification

In this project, I will be doing an Image Classification of Fruits that has over 40 classes (as required by RDAI). I will first perform basic data exploratatory on the dataset and some preprocessing before training the model. However, to improve accuracy and to prevent overfitting, I will be applying some ML techniques (listed below) that I have learnt during the course as well as my own personal study.

- Data augmentation 

Data augmentation is a technique used to artificially expand and diversify a dataset by applying various transformations to existing data, enhancing model robustness and generalization.
- Batch normalization

Batch normalization streamlines the training of deep neural networks by standardizing layer inputs within each mini-batch, resulting in a stabilized learning process and a substantial decrease in the necessary training epochs for deep network convergence.
- Weight Decay

Weight decay is employed to restrain weight magnitudes and prevent gradient explosion. By adding the L2 norm of the weights to the loss, each iteration of the network optimizes both the model weights and the loss, ensuring that the weights remain manageable and averting issues of gradient explosion.

- Gradient clipping

Gradient clipping is a technique to mitigate exploding gradients in neural networks by restricting the magnitude of the gradient. Various methods exist for computing gradient clipping, with a common approach being to rescale gradients to ensure their norm does not exceed a specified value.

# **Dataset Used**

I will be using a dataset from Kaggle (https://www.kaggle.com/moltean/fruits). Below are the few characteristics of the dataset.

Total number of images: 90483.

Training size used: 67692 images (one fruit or vegetable per image).

Test size used: 22688 images (one fruit or vegetable per image).

Total number of classes: 131 (fruits and vegetables).

Image size: 100x100 pixels.

Different species of the same fruit (apple for instance) are stored as belonging to different classes.

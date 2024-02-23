# Deep-Learning-Projects
Overview of some recent deep learning projects, all implemented in **PyTorch**.


# Description of the Projects

## Projects on Feed Forward Networks

- **Project: Adding Machine**
  + In this project, we build a feedforward neural network (FFN) capable of adding two integers between -10 and 10. To ensure the consistency of our results, we conduct an experiment by constructing the same model architecture ten times and evaluating the obtained results. The file that contains the code is  ``adding_machine.ipynb``.

      
- **Project: Wine Dataset**
    +  In **Part 1** of this project, we utilize the wine-quality dataset to build a simple deep learning model for classifying wine quality based on physicochemical tests. Furthermore, we conduct a parametric experiment, testing various batch sizes and comparing their accuracy. Finally, we evaluate the outcomes derived from the experiment. The file that contains the code is ``experiment_minibatch_size.ipynb``.
       
    +  In **Part 2** of this project, we aim to predict missing values for the 'residual sugar' column in the wine dataset. Since the original wine dataset does not contain any missing values in the 'residual sugar' column, we need to artificially introduce them. To create these missing values, we randomly select 10 rows where we set the 'residual sugar' to NaN. Subsequently, we build a regression model to predict these missing values. Finally, we evaluate the results obtained from the model. The name of the code file is ``predict_missing_residual_sugar.ipynb``.
      
    +  **Part 3** of this project involves comparing two weight initialization methods, Kaiming and Xavier, using the wine dataset. After the experiment, we evaluate the results with T-tests. The name of the code file is ``Kaming_Xavier_weight_initialization.ipynb``.
 

- **Project: MNIST Dataset**
   + The objective of **Part 1** in this project is to evaluate the performance of a deep learning model on unseen data. For this purpose, we will train a model using the MNIST database, comprising images of handwritten digits from 0 to 9. To assess the impact of unseen data, we intend to exclude the digit 7 from the training set. Subsequently, we will evaluate the model's predictions on images containing the digit 7. The file that contains the code is ``mystery of the missing 7.ipynb``.
 
## Projects on Autoencoders

- **Project: Autoencoder - How many units?**
  +  In this project, our goal is to create a deep learning model with an autoencoder architecture. Additionally, we conduct a parametric experiment to answer the question: What is the optimal combination of encoding/decoding units and latent units within a specified range, aiming for minimal loss? After conducting the experiment, we visualize and evaluate the obtained results. The file that contains the code is ``how_many_units.ipynb``.

## Projects on Convolutional Neural Networks
- **Project: Autoencoder on Occcluded Gaussians**
  +  In this project, we build an CNN based autoencoder capable of removing occlusions on Gaussians. To achieve our goal, we create two datasets consisting of images of a two-dimensional Gaussian distribution. The images in both datasets are almost the same but differ in one single aspect. In one dataset, we artificially introduce occlusions consisting of random bars, whereas in the other dataset, the images remain in their original state without introducing occlusions. Next, we construct a CNN autoencoder with an architecture designed to remove occlusions on Gaussians. Finally, we evaluate and visualize the results obtained from our model. The file that contains the code is ``AEs_on_occluded_Gaussians.ipynb``.
- **Project: CIFAR-Autoencoder**
  + In this project, we construct a Convolutional Neural Network (CNN)-based autoencoder to encode images from the CIFAR-10 dataset. The name of the code file is `CIFAR_Autoencoder.ipynb`.
- **Project: Classification on the Fashion-MNIST Dataset**
  + In this project, we construct a Convolutional Neural Network (CNN) to classify the Fashion-MNIST dataset into its ten different fashion categories. After constructing the CNN, we evaluate and plot the obtained results. The name of the code file is `classification_FashionMNIST.ipynb`.
- **Project: Psychometric Functions in CNNs**
  + In this project, we are building a CNN that is able to simulate a psychometric function. A psychometric function maps the decision probability in binary classification studies when the stimuli are continuous. Specifically, we aim to simulate a psychometric function capable of deciding whether a given image contains a vertical or horizontal line.
  + To achieve this goal, we build a CNN model and train it on 1x30x30 images of Gaussian noise plus random vertical or horizontal lines (see the picture below). We then evaluate and plot our results.
<br/><br/>
![](images/guassians_with_horizontal_vertical_lines.png)
<br/><br/>
  + In a further step, we explore our previously trained model by subjecting it to new images. These images, of shape 1x30x30, differ from the training images because they have not only horizontal and vertical lines but also lines with a slope ranging from -30 to 30 (see the picture below). Next, we evaluate what is the predicted outcome on those images and plot again our results. The name of the code file is `psychometric_functions_in_CNNs.ipynb`.
<br/><br/>
![alt text](https://github.com/marvinneugebauer/Deep-Learning-Projects/blob/main/images/lines_with%20_different_slopes.png)




  

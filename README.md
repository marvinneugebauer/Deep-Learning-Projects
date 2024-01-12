# Deep-Learning-Projects
Overview of some recent deep learning projects, all implemented in **PyTorch**.


# Description of the Projects

## Projects on Feed Forward Networks

- **Project: Adding Machine**
    +  In this project, we build a feedforward neural network (FFN) capable of adding two integers between -10 and 10. To ensure the consistency of our results, we conduct an experiment by constructing the same model architecture ten times and evaluating the obtained results. The file that contains the code is  ``adding_machine.ipynb``.

      
- **Project: Wine Dataset**
    +  In **Part 1** of this project, we utilize the wine-quality dataset to build a simple deep learning model for classifying wine quality based on physicochemical tests. Furthermore, we conduct a parametric experiment, testing various batch sizes and comparing their accuracy. Finally, we evaluate the outcomes derived from the experiment. The file that contains the code is ``experiment_minibatch_size.ipynb``.
       
    +  In **Part 3** of this project, we aim to predict missing values for the 'residual sugar' column in the wine dataset. Since the original wine dataset does not contain any missing values in the 'residual sugar' column, we need to artificially introduce them. To create these missing values, we randomly select 10 rows where we set the 'residual sugar' to NaN. Subsequently, we build a regression model to predict these missing values. Finally, we evaluate the results obtained from the model. The name of the code file is ``predict_missing_residual_sugar.ipynb``.
      
    +  **Part 4** of this project involves comparing two weight initialization methods, Kaiming and Xavier, using the wine dataset. After the experiment, we evaluate the results with T-tests. The name of the code file is ``Kaming_Xavier_weight_initialization.ipynb``.
 

- **Project: MNIST Dataset**
   + The objective of **Part 1** in this project is to evaluate the performance of a deep learning model on unseen data. For this purpose, we will train a model using the MNIST database, comprising images of handwritten digits from 0 to 9. To assess the impact of unseen data, we intend to exclude the digit 7 from the training set. Subsequently, we will evaluate the model's predictions on images containing the digit 7.
 
## Projects on Autoencoders
  

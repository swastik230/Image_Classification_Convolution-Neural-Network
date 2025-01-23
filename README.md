# Image_Classification_Convolution-Neural-Network
CNN Classification Part:-1 Series
                                                                                                         
  a>IMPORTS:-The necessary libraries are imported, including PyTorch and torchvision.

  b>Data Loading:-
                                                                                                               
  -The CIFAR-10 dataset is loaded and transformed. The images are converted to tensors and normalized.
                                                                                                               
  -Data loaders are created for both the training and test datasets.

  c>CNN Model Definition:-

  -A simple CNN architecture is defined with three convolutional layers followed by two fully connected layers.

  -The 'forward' method defines how the input data passes through the network.

  d>Model Instantiation:-

  -An instance of the CNN model is created.

  -The loss function (Cross Entropy Loss) and optimizer (Adam) are defined.

 e>Training Loop:-

  -The model is trained for 10 epochs. For each batch, gradients are reset, a forward pass is performed, loss is calculated, and weights are updated.

 f>Evaluation:-

  -The model's performance is evaluated on the test dataset, and the accuracy is printed.


CNN Classification Part:-2 Series

a>Imports:-The necessary libraries are imported, including TensorFlow and Keras layers/models.
 
b>Data Loading:-

 -The CIFAR-10 dataset is loaded using cifar10.load_data().

 -The pixel values of the images are normalized to the range [0, 1] by dividing by 255.0.

c>Model Compilation and Training:-

 -The model is compiled with the Adam optimizer and categorical crossentropy loss function.

 -The model is trained for 10 epochs with a batch size of 64, and validation data is provided.

 d>Model Evaluation:-

 -The model's performance is evaluated on the test dataset, and the accuracy is printed.

 

  


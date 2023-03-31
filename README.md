<h1 align=center>CGAN Implementation Using CNN</h1>

------------------------------------------------------------------------

We use GAN inorder to generate data. In this project we use conditional GAN which generate examples for the classes we want.

------------------------------------------------------------------------
## Steps:   

* Import libraries
* define generator network
* define discriminator network
* get MNIST dataset and prepar it for training
* define functions:
    * Function for creating one-hot vectors for the labels
    * Function for combining two vectors
    * Function for getting the size of the conditional input dimensions
    * weights initialization
    * Function for visualizing images
* Training the model

------------------------------------------------------------------------

## Parameters Used:

* criterion: the loss function => (BCEWithLogitsLoss())

* n_epochs: the number of times you iterate through the entire dataset when training =>(30)

* z_dim: the dimension of the noise vector =>(64)

* display_step: how often to display/visualize the images =>(300)

* batch_size: the number of images per forward/backward pass =>(128)

* lr: the learning rate =>(0.0002)

* device: the device type =>(cuda)


------------------------------------------------------------------------

## Deploying a GAN to a cloud-based service requires several steps:
**Note:** Copy
### Prepare the GAN model:
The first step is to prepare the GAN model for deployment. This includes converting the model to a format that can be used by the cloud service (such as TensorFlow or PyTorch), saving the model weights and architecture, and creating any necessary preprocessing.

### Choose a cloud-based service

### Set up the cloud service:
Once a cloud service has been selected, the next step is to set up the infrastructure. This typically involves creating a virtual machine (VM) or container instance, configuring the necessary software and libraries, and creating an API endpoint for the GAN.

### Deploy the GAN:
The next step is to deploy the GAN to the cloud service. This involves uploading the model weights and architecture, along with any necessary preprocessing or post-processing functions. The GAN can then be integrated with the API endpoint to enable real-time image generation.



------------------------------------------------------------------------
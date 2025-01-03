## CIFAR10-using-CNN-and-ResNet

**Summary: Project, dataset**
It is a image classification project based on a standard dataset. First of all, ResNet backbone architecture is shortlisted on comparison of how well several contemporary algorithms perform on comparable dataset. The Residual Network (ResNet) is selected for the project based on the framework's historical performance on sizable datasets, and the resource constraints to perform the implementation of the model for image classification on CIFAR10 dataset. To reduce losses, a basic ResNet has a residual block at the conclusion of each convolution layer. Consequently, a residual block is added to each layer of a CNN in place of a loss function.

CIFAR10 is a dataset of 60000 labeled 32x32 color images in 10 classes, containing 6000 images in each class. Ten thousand test images and fifty thousand training images are included. Five training batches and one test batch, each containing 10,000 images, make up the dataset. There are precisely 1000 randomly chosen images from each class in the test batch. The remaining photographs are arranged randomly in the training batches, albeit certain training batches could include more images from one class than another. The training batches are made up of precisely 5000 images from each class.

**Steps to replicate the results: Provide clear instructions for setting up and running the code**
It is an executable Jupyter notebook. You can run it and experiment with the code examples in a couple of ways: using free online resources (recommended) or on your computer.

Option 1: Running using free online resources (1-click, recommended)
The easiest way to start executing the code is to click the Run button at the top of this page and select Run on Colab. Google Colab is a free online platform for running Jupyter notebooks using Google's cloud infrastructure. You can also select "Run on Binder" or "Run on Kaggle" if you face issues running the notebook on Google Colab.

Option 2: Running on your computer locally
To run the code on your computer locally, you'll need to set up Python, download the notebook and install the required libraries. We recommend using the Conda distribution of Python. Click the Run button at the top of this page, select the Run Locally option, and follow the instructions.

Using a GPU for faster training
You can use a Graphics Processing Unit (GPU) to train your models faster if your execution platform is connected to a GPU manufactured by NVIDIA. Follow these instructions to use a GPU on the platform of your choice:

Google Colab: Use the menu option "Runtime > Change Runtime Type" and select "GPU" from the "Hardware Accelerator" dropdown.

Kaggle: In the "Settings" section of the sidebar, select "GPU" from the "Accelerator" dropdown. Use the button on the top-right to open the sidebar.

Binder: Notebooks running on Binder cannot use a GPU, as the machines powering Binder aren't connected to any GPUs.

Linux: If your laptop/desktop has an NVIDIA GPU (graphics card), make sure you have installed the NVIDIA CUDA drivers.

Windows: If your laptop/desktop has an NVIDIA GPU (graphics card), make sure you have installed the NVIDIA CUDA drivers.

macOS: macOS is not compatible with NVIDIA GPUs

# Neural Style Transfer Project
Project Overview

This project implements Neural Style Transfer, a deep learning technique that applies the artistic style of one image (style image) onto another (content image) to create a combined output image that reflects the content in the style of the specified artwork.
Key Features

    Content Image: The image you want to apply the artistic style to.
    Style Image: The artistic image whose style you want to transfer.
    Output: The final image that blends both the content and style.

How It Works

The model uses a pre-trained Convolutional Neural Network (CNN), such as VGG19, to extract both style and content features from images. By minimizing a loss function that considers both content and style representation, the model adjusts the pixel values of the content image to match the style of the style image.
Loss Function Breakdown:

    Content Loss: Ensures that the output image retains the structure of the content image.
    Style Loss: Enforces that the texture and patterns of the style image are present in the final output.
    Total Variation Loss: Regularizes the image to ensure smooth transitions in pixel values, reducing noise.

Results

The final images generated show the successful merging of the content image with the artistic style. You can check the results in the Google Colab Notebook linked below.
Colab Notebook

You can run and test the project directly through the following Google Colab link:

[Google Colab Notebook](https://colab.research.google.com/drive/1d0xK-hnbmSJKh2__niXPkkjVz8mZfa1R?usp=sharing)
Running the Project

    Clone the repository or download the files.
    Open the Google Colab notebook and run it.
    Make sure you upload your own content and style images (or use the provided ones).
    The code will automatically generate the stylized image.

Requirements

You don't need to install anything if you're running this on Colab. Otherwise, ensure you have the following:

    Python 3.x
    TensorFlow
    NumPy
    Matplotlib

Images and Output

here is my google drive link for input images https://drive.google.com/drive/folders/1mi3BT3Z6S4K3BXDONC7goBvVqbGQNtdu?usp=drive_link

All images and results can be viewed directly in the Colab notebook, where you'll see the content image, style image, and the generated image.

# Link to the output file:
https://drive.google.com/drive/folders/1XAa8-RZnJV8Weq2qpW1ET-0IulD36Q0k?usp=sharing

It seems that matplotlib requires uint8 for the colormaps, so the pixel depth is lower, but I think the image quality is good. You can also see on the main file (denoising.ipynb) the whole process.
# Satellite-Denoising
Repo containing a Denoising Technique for satellite images.
In the script experiments.ipynb you will find a comparison between different methods, some of which are briefly explained. (I had to close all outputs because the file was too big).
# The main file is denoising.ipynb, which contains the whole task.
A very interesting idea for this would be to train an autoencoder in an unsupervised manner, taking clean images and adding noise and using this as an input, then comparing the output image with the ORIGINAL image, so it trains to take a noisy image and outputs a clean one.

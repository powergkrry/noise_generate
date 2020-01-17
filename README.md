# Image Blind Denoising With Generative Adversarial Network Based Noise Modeling
This is the implementation of GCBD paper Using Keras. You can find the original paper at [here](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Image_Blind_Denoising_CVPR_2018_paper.pdf).

## Prepare data
You can generate Noise block seperately by using generate_noise_patch.ipynb code.
### Sample images
60079.png - From BSD300, https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/

night.jpg - From https://www.flickr.com/people/52836039@N02/

## Execute the code(GCBD) with Jupyter notebook
### **This is not an official code for the paper.**
Specific model parameters that were not given on the paper can be different from the original paper.

### Run code
This code is for generating gaussian noise with a certain level.
You can change ```X_train``` and ```noise``` in train function to feed different datasets.

### Results
![Generated Images](https://github.com/powergkrry/noise_generate/blob/master/images/image_1600.png)

The current model has an issue with mode collapse.

# Version
tensorflow 2.0

# License MIT

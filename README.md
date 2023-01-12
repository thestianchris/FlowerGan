# FlowerGan
INTRODUCTION

Generative Deep Learning

This coursework will explore the use of generative adversarial networks (GANs) to generate synthetic images of flowers. The techniques used within this study will follow the workings of Francois Chollet within the Deep Learning With Python textbook.

GANs a class of deep learning models designed for generating new, previously unseen data that is similar to a given training dataset. GANs consist of two main components: a generator network and a discriminator network. The generator network is responsible for creating new data, while the discriminator network is responsible for distinguishing the generated data from the real data. The two networks are trained simultaneously in an adversarial manner, where the generator tries to create data that can fool the discriminator into thinking it's real, and the discriminator tries to correctly identify the generated data as fake. The training process continues until the generator is able to produce data that is indistinguishable from real data to the discriminator.

The Dataset

The dataset being used is the Oxford 102 Category Flower Dataset, available at https://www.robots.ox.ac.uk/~vgg/data/flowers/102/, containing 102 categories of flowers found in the UK. Each class contains between 40-258 samples with an overall sample size of 8189. To use the images within the model, they must be resized and preprocessed into a tensorflow dataset object that is normalized to squish the pixel values between 0 and 1.

Workflow

To successfully implement a GAN model, the tweaking of varius hyperparameters will take place along with regularization techniques in order to find the most successful model with the intent of producing the most "artistic" or "realistic" looking flower generations. This tuning process includes adjustments to the optimizer, learning rate, layer units, and number of iterations for each model.

The ultimate goal of this research is to identify the specific changes to the GAN model that result in the highest quality generated flower images, as determined by human interpretation.

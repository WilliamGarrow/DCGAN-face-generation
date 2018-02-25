# Face Generation | Deep Convolutional Generative Adversarial Network

### Face generation exhibited by using a deep convolutional generative adversarial network (DCGAN) on the CelebA dataset to generate images of novel and realistic human faces.


This is the fifth project in Udacity's [Deep Learning Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree--nd101). The program covers topics like Keras and TensorFlow, convolutional and recurrent networks, deep reinforcement learning, and GANs. 

In this project, I developed a Generative Adversarial Network (GAN) in TensorFlow to generate new realistic images of faces based on the examples from the CelebFaces Attributes Dataset (CelebA) which contains 200K celebrity images, each with 40 attribute annotations.
The approach is based on creating two separate deep neural networks competing with each other, the generator and the discriminator, where the generator will generate fake images that in an effort to fool the discriminator as real images. 
They compete until the discriminator cannot distinguish between the real and the generated images by continually training and calculating the loss while creating the optimization operations for the GANs.

### My Project Submission
[Jupyter Notebook](https://github.com/WilliamGarrow/DCGAN-face-generation/blob/master/dlnd_face_generation.ipynb)




# Building a generative model that creates X-ray images of hands

<img src="https://drive.google.com/uc?id=1LubLuuyiJwyDNRd2Wj0vaA0Ek2AtAFxH" width="500"/>


<br>

## Introduction:
This project aims to generate realistic X-Ray images of hands using Generative Adversarial Networks (GANs). GANs are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. They consist of two neural networks, a generator and a discriminator, that contest with each other in a game. The goal is to create synthetic data that is indistinguishable from real data.



## Dataset
We have 8000 samples available in the repository under the folder `real_hands` that we will use to train the GAN.

## Features

- Generate realistic X-Ray images of hands.
- Train GAN models using a dataset of X-Ray hand images.
- Evaluate the quality of generated images.
- Save and load trained models for future use.

The GAN model consists of two neural networks:

- **Generator**: Takes random noise as input and generates synthetic X-Ray images.
- **Discriminator**: Takes an image as input and classifies it as real or fake.

Both networks are trained simultaneously: the generator tries to create realistic images to fool the discriminator, while the discriminator aims to distinguish between real and fake images.

## Results
Generated images and evaluation results will be stored in the GAN_Hands/ directory. Example images and metrics are displayed in the notebooks.

## License
This project is licensed under the MIT License. See the LICENSE file for details.




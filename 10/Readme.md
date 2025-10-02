# **PROJECT: Facial Gender Transformation using GANs**

##Objective:
This project explores how the latent space of a pre-trained Generative Adversarial Network (GAN) can be manipulated to control semantic attributes—in this case, gender. The aim was to generate a sequence of 10 images demonstrating a smooth transition from a masculine-presenting face to a feminine-presenting one.

##Methodology:

1. Latent Vector Initialization: A random latent vector was sampled to generate the base face.

2. Gender Vector Application: A pre-computed “gender vector” was used to represent the direction of gender variation in latent space.

3. Linear Interpolation: The gender vector was applied with gradually changing multipliers, creating a progression from one end of the spectrum to the other.

4. Image Generation: Each modified latent vector was passed through the GAN, producing a coherent transformation sequence.

##Conclusion:
The results highlight the ability of GANs to not only generate photorealistic faces but also edit attributes in a controlled and interpretable way. This demonstrates the potential of GANs for advanced tasks such as facial editing, style transfer, and creative AI applications.

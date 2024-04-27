# Adversarial-ML

### FGSM (Fast Gradient Sign Method)



![image](https://github.com/LyaSofya/Adversarial-ML/assets/98537818/20930210-cdb0-47ae-a0d1-91137363758b)


The fast gradient sign method works by using the gradients of the neural network to create an adversarial example. 
For an input image, the method uses the gradients of the loss with respect to the input image to create a new image that maximises the loss. 
This new image is called the adversarial image. 


This can be summarised using the following expression:

![image](https://github.com/LyaSofya/Adversarial-ML/assets/98537818/269b8e42-b12c-4b5a-824f-f59bebdb01e2)



# vanilla-cgan-tf2
Simple TensorFlow 2.0 implementation for Conditional Generative Adversarial Network  
I trained the CGAN to generate samples from a particular class label

### CGAN
CGAN is an extension to Generative Adversarial Networks where both of the generator and discriminator are conditioned on some extra information y.
y could be any thing such as class labels or data from other modalities.

![Alt text](images/figure.png?raw=true "Title")

##### CGAN value function

![Alt text](images/equation.png?raw=true "Title")


In the notebook source code I conditioned it by feeding the class label into both of the discriminator and generator. After training you could use the generator to generate samples from a particular class label.



### References
- [Conditional GAN paper](https://arxiv.org/abs/1411.1784)

### Contact
To ask questions or report issues, please open an issue on the [issues tracker](https://github.com/eng-amrahmed/vanilla-cgan-tf2/issues)

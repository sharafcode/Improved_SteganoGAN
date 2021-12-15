# Improved_SteganoGan.
Improving the StegnoGan network with the recent advances in the GAN like using Spectral normalization or working with DCGANs and other variants of the gans

NOTE:
This code is cloned from the great authors of the original SteganoGAN you can find it [here](https://github.com/DAI-Lab/SteganoGAN)


## What we did ?

We removed batch normalization and added the spectral normalization layers to GANs which this should improve the SteganoGan.

------------------------


**You will find our modifactions in the following files**

```
steganogan/critics.py  #This the main discrimnator function we added the Spectral normalization layers
steganogan/models.py  #Slight modifications in the optimizers and the model loss
```

**To replicate our results follow the notebook and run it on a google Colab**
`research/Experiments.ipynb`

------------------------------

## References

```
1. Miyato, T., Kataoka, T., Koyama, M., & Yoshida, Y. (2018). Spectral Normalization for Generative Adversarial Networks.
2. Zhang, K. A., Cuesta-Infante, A., Xu, L., & Veeramachaneni, K. (2019). SteganoGAN: High Capacity Image Steganography with GANs.

```

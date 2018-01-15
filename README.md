# Mnist/Cifar10 CVAE and VQ-VAE

This is an implementation of the VQ-VAE (Vector Quantized Variational Autoencoder) and Convolutional Varational Autoencoder.
 from [Neural Discrete representation learning](https://arxiv.org/pdf/1711.00937.pdf) for compressing MNIST and Cifar10.
The code is based upon [pytorch/examples/vae](https://github.com/pytorch/examples/tree/master/vae).

```bash
pip install -r requirements.txt
python main.py
```

# TODO: 
- [ ] Imporve results on cifar

- [X] Merge VAE and VQ-VAE for MNIST and Cifar to one script

# Acknowledgement
[tf-vaevae](https://github.com/hiwonjoon/tf-vqvae) for a good reference.

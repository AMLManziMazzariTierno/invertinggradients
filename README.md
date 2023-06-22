# Inverting Gradients - How easy is it to break Privacy in Federated Learning?

---------------------

**Update Feb 2022: A modernized implementation of this attack (and many other attacks) is included in our newest framework for privacy attacks in FL:**

**https://github.com/JonasGeiping/breaching**

---------------------


This repository is an implementation of the reconstruction algorithm discussed in
```
Jonas Geiping, Hartmut Bauermeister, Hannah Dröge, and Michael Moeller. 
Inverting Gradients -- How Easy Is It to Break Privacy in Federated Learning?, 
March 31, 2020. 
https://arxiv.org/abs/2003.14053v1.

```
which can be found at https://arxiv.org/abs/2003.14053


### Quick Start
"ResNet20 - trained.ipynb" for the attack that reconstruct a single image from trained ResNet20.

Use models/instaHideResNet20_k=1.pt file in previous notebook for the attack on instaHide trained net.

"ResNet20 - Recovering multiple CIFAR-100 images.ipynb" for the attack that reconstruct multiple images from trained ResNet20.

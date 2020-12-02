# Awesome GAN papers

By all means, this is not a complete list of GAN-related papers.  We are
specifically looking for generative modeling techniques to bridge the gap
between two domains, something similar to the CycleGAN. This repo also includes
historical important GAN papers, their difficulties in training,
and various techniques to overcome such difficulties and improve the performance.

## GANs between domains
In reverse chronological order 

- [x] [StarGANv2](https://arxiv.org/abs/1912.01865)
- [ ] [CartonGAN](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf)
- [ ] [Resolution Dependant GAN Interpolation for Controllable Image Synthesis Between Domains](https://arxiv.org/abs/2010.05334v1)
- [ ] [CycleGAN](https://arxiv.org/abs/1703.10593)

## Interpreting GANs

- [ ] [White-box Cartoonization](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Learning_to_Cartoonize_Using_White-Box_Cartoon_Representations_CVPR_2020_paper.pdf)
- [Analyzing and Improving the Image Quality of StyleGAN](https://arxiv.org/abs/1912.04958)

## GANs for high-resolution images
In reverse chronological order 

- [ ] [StyleGANv2](https://arxiv.org/abs/1912.04958)
- [BigGAN](https://arxiv.org/pdf/1806.06778.pdf)
- [BigBiGan](https://arxiv.org/abs/1907.02544)

## Classic GANs
In chronological order. 

- [x] [GAN](https://arxiv.org/pdf/1406.2661.pdf)
- [x] [GAN Tutorial](https://arxiv.org/pdf/1701.00160.pdf)
- [ ] [CGAN](https://arxiv.org/abs/1411.1784)
- [DCGAN](https://arxiv.org/abs/1511.06434)
- [WGAN](https://arxiv.org/abs/1701.07875)

## The other side of the coin
It is hard to find a paper dedicated on the failures of the GAN techniques.  But
some papers may have some content describing what problems the previous GAN
has.

- [Fig1,Fig6,StyleGANv2](https://arxiv.org/abs/1912.04958)
- [Intro,WGAN](https://arxiv.org/abs/1701.07875)

## The details matter
There are many techniques to improve GAN's performance. And some of them are
tried and true. 

- [ ] [Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498)
- [ ] [Which Training Methods for GANs do actually Converge?](https://arxiv.org/abs/1801.04406) 
- [ ] [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/abs/1703.06868)
- [ ] [The Unusual Effectiveness of Averaging in GAN Training](https://arxiv.org/abs/1806.04498)


## General

- [ ] [Underspecification Presents Challenges for Credibility in Modern Machine Learning” might of interest to ML enthusiasts](https://arxiv.org/abs/2011.03395) 

## Implementations

- [PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN)


## Fun Reads

- [Gwern's blog](gwern.net/)

## Under consideration

- [Graph Generative Adversarial Networks for Sparse Data Generation in High Energy Physics](https://arxiv.org/abs/2012.00173) Using GAN as a "fast simulation" to replace Geant4.  While this is not a goal of LS4GAN the use of sparse data on graphs may be a useful technique to handle LS4GAN's anticipated large but sparse events.

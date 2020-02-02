# pytorch_practice
A code list of practice using PyTorch. I wrote code using Jupyter Notebook.

Inspired by [`some recommendation`](https://www.reddit.com/r/MachineLearning/comments/8vmuet/d_what_deep_learning_papers_should_i_implement_to/) and others.

## Contributor
* [Ho Seong Lee](https://github.com/hoya012)

## Requirements
```
Python 3.5
PyTorch == 0.4.0
TorchVision == 0.2.1
```

## Contents
### Image Classification
- ResNet [`[pdf]`](https://arxiv.org/abs/1704.06904) [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Classification/ResNet.ipynb)
- Xception [`[pdf]`](https://arxiv.org/abs/1610.02357) [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Classification/Xception.ipynb)
- MobileNet [`[pdf]`](https://arxiv.org/abs/1704.04861) [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Classification/MobileNet.ipynb)

### Image Generative Models
- Vanilla AutoEncoder  [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Generative_model/Vanilla_AE.ipynb)  
   - Result of Vanilla AutoEncoder. Odd line is original inputs, and Even line is AE outputs.  
   
<p align="center">
  <img width="300" src="/result_images/result_AE.png" "Result of Vanilla AutoEncoder. Odd line is original inputs, and Even line is AE outputs ">
</p>

- Denoising AutoEncoder [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Generative_model/Denoising_AE.ipynb)  
   - Result of Denoising AutoEncoder. Odd line is original inputs, and Even line is DAE outputs.  
   
<p align="center">
  <img width="300" src="/result_images/result_DAE.png" "Result of Denoising AutoEncoder. Odd line is original inputs, and Even line is DAE outputs ">
</p>


- Vanilla GAN [`[pdf]`](https://arxiv.org/abs/1406.2661) [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Generative_model/GAN.ipynb)
   - Result of Vanilla GAN with MNIST.  
   
<p align="center">
  <img width="300" src="/result_images/result_GAN.png" "Result of Vanilla GAN with MNIST ">
</p>

- DCGAN [`[pdf]`](https://arxiv.org/abs/1511.06434) [`[code]`](https://github.com/hoya012/pytorch_practice/blob/master/Image_Generative_model/DCGAN.ipynb)
   - Result of DCGAN with FashionMNIST.  
   
<p align="center">
  <img width="300" src="/result_images/result_DCGAN.png" "Result of DCGAN with FashionMNIST ">
</p>


## To do list
### Image Classification
- SENet [`[pdf]`](https://arxiv.org/abs/1709.01507)
- NASNet-A [`[pdf]`](https://arxiv.org/abs/1707.07012)

### Image Generative Models

- WGAN [`[pdf]`](https://arxiv.org/abs/1701.07875)
- LSGAN [`[pdf]`](https://arxiv.org/abs/1611.04076)
- CGAN [`[pdf]`](https://arxiv.org/abs/1411.1784)
- infoGAN [`[pdf]`](https://arxiv.org/abs/1606.03657)
- BGAN [`[pdf]`](https://arxiv.org/abs/1702.08431)
- BEGAN [`[pdf]`](https://arxiv.org/abs/1703.10717)
- Pix2Pix [`[pdf]`](https://arxiv.org/abs/1611.07004)
- CycleGAN [`[pdf]`](https://arxiv.org/abs/1703.10593)

### Image Super-Resolution
- VDSR [`[pdf]`](https://arxiv.org/abs/1511.04587) 
- EDSR [`[pdf]`](https://arxiv.org/abs/1707.02921) 

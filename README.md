### Image Denoising via Bandwise Adaptive Modeling and Regularization Exploiting Nonlocal Similarity (TIP 2016) [[pdf]](https://ieeexplore.ieee.org/document/7406719/)

## Introduction
This paper proposes a new image denoising algorithm based on adaptive signal modeling and regularization. It improves the quality of images by regularizing each image patch using bandwise distribution modeling in transform domain. Instead of using a global model for all the patches in an image, it employs content-dependent adaptive models to address the non-stationarity of image signals and also the diversity among different transform bands. The distribution model is adaptively estimated for each patch individually. It varies from one patch location to another and also varies for different bands. In particular, we consider the estimated distribution to have non-zero expectation. To estimate the expectation and variance parameters for every band of a particular patch, we exploit the nonlocal correlation in image to collect a set of highly similar patches as the data samples to form the distribution. Irrelevant patches are excluded so that such adaptively learned model is more accurate than a global one. The image is ultimately restored via bandwise adaptive soft-thresholding, based on a Laplacian approximation of the distribution of similar-patch group transform coefficients. Experimental results demonstrate that the proposed scheme outperforms several state-of-the-art denoising methods in both the objective and the perceptual qualities.


## Citation
If you find our code helpful in your resarch or work, please cite our paper.
```
@article{xiong2016image,
  title={Image denoising via bandwise adaptive modeling and regularization exploiting nonlocal similarity},
  author={Xiong, Ruiqin and Liu, Hangfan and Zhang, Xinfeng and Zhang, Jian and Ma, Siwei and Wu, Feng and Gao, Wen},
  journal={IEEE Transactions on Image Processing},
  volume={25},
  number={12},
  pages={5793--5805},
  year={2016},
  publisher={IEEE}
}
```

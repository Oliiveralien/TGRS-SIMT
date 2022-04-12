# TGRS-SIMT

Code, results and evaluations of the paper ''Efficient Pyramidal GAN for Versatile Missing Data Reconstruction in Remote Sensing Images'' submitted for TGRS.

## Introductoin
Missing data reconstruction is a classical yet challenging problem in remote sensing image processing due to the complex atmospheric environment and variability of satellite sensors. Most of the contemporary reconstruction methods either handle only one specific task or require supplementary data, while the single-input for multi-task reconstruction has not been explored yet. In this paper we propose a novel Generative Adversarial Network-based unified framework for missing remote sensing image reconstruction, which is capable of various reconstruction tasks given only single source data as input.
Specifically, we first propose a Mask Extraction Network (MEN) to obtain a united soft mask, which represents the intrinsic prior under various scenarios and indicates not only location but context information. The versatility of mask extraction enables the multi-task reconstruction of remote sensing images. 
Besides, we propose a Unified Inpainting Network (UIN) to repair diverse degraded images. Being specifically tailored for remote sensing images, Dilated pyramidal convolutions (DPC) and an Attention Fusion Mechanism (AFM) are introduced to further improve the feature extraction ability and thus exhaustly leveraging the single-input information.
Extensive experiments demonstrate the uncompromising performance of the proposed method against state-of-the-art multi-input methods on diverse missing restoration. 
Moreover, further exploration shows the potential of the proposed method to utilize joint spatio-spectral-temporal information, which is evaluated to outperform existing competitors on remote sense images.

## Some Results
Mask data: [DATA](https://drive.google.com/file/d/1p0Q1DO7J8Igj4-DZRonQhQOL2LsPGrD5/view?usp=sharing)

![All text](https://github.com/Oliiveralien/Inpainting-on-RSI/blob/master/pics/newSLC.png)


## Training & Test
Try `train.py` and `test.py`.

## Code
* Code will be available soon.
* Pretrained model will be uploaded asap.

## Contact
Please contact me if there is any question. (Chao Wang oliversavealien@gmail.com)

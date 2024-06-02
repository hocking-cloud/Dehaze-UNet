# Dehaze-UNet
This is the code for the paper Dehaze-UNet: A Lightweight Network Based on UNet for Single Image Dehazing.
If you refer to our code, please cite our work:
@Article{electronics13112082,
AUTHOR = {Zhou, Hao and Chen, Zekai and Li, Qiao and Tao, Tao},
TITLE = {Dehaze-UNet: A Lightweight Network Based on UNet for Single-Image Dehazing},
JOURNAL = {Electronics},
VOLUME = {13},
YEAR = {2024},
NUMBER = {11},
ARTICLE-NUMBER = {2082},
URL = {https://www.mdpi.com/2079-9292/13/11/2082},
ISSN = {2079-9292},
ABSTRACT = {Numerous extant image dehazing methods based on learning improve performance by increasing the depth or width, the size of the convolution kernel, or using the Transformer structure. However, this will inevitably introduce many parameters and increase the computational overhead. Therefore, we propose a lightweight dehazing framework: Dehaze-UNet, which has excellent dehazing performance and very low computational overhead to be suitable for terminal deployment. To allow Dehaze-UNet to aggregate the features of haze, we design a LAYER module. This module mainly aggregates the haze features of different hazy images through the batch normalization layer, so that Dehaze-UNet can pay more attention to haze. Furthermore, we revisit the use of the physical model in the network. We design an ASMFUN module to operate the feature map of the network, allowing the network to better understand the generation and removal of haze and learn prior knowledge to improve the network’s generalization to real hazy scenes. Extensive experimental results indicate that the lightweight Dehaze-UNet outperforms state-of-the-art methods, especially for hazy images of real scenes.},
DOI = {10.3390/electronics13112082}
}



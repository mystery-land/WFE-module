# WFE-module
The official implementation of **WFE: Wavelet Transform Feature Enhancement for Semantic Segmentation of Remote Sensing Images**.

## Usages
The code will be updated later.

## Abstract
With developments in deep learning, semantic segmentation of remote sensing images has made great progress. Currently, mainstream methods are based on convolutional neural networks (CNNs) or vision transformers. However, these methods are not very effective in extracting features from remote sensing images, which are usually of high resolution with plenty of detail. Operations including downsampling will cause the loss of such features. To address this problem, we propose a novel module called Hierarchical Wavelet Feature Enhancement (WFE). The WFE module involves three sequential steps: (1) performing multi-scale decomposition of an input image based on the discrete wavelet transform; (2) enhancing the high-frequency sub-bands of the input image; and (3) feeding them back to the corresponding layers of the network. Our module can be easily integrated into various existing CNNs and transformers, and does not require additional pre-training. We conducted experiments on the ISPRS Potsdam and ISPRS Vaihingen datasets, with results showing that our method improves the benchmarks of CNNs and transformers while performing little additional computation.

## Citations
```latex
@article{rs15245644,
    author = {Li, Yifan and Liu, Ziqian and Yang, Junli and Zhang, Haopeng},
    title = {Wavelet Transform Feature Enhancement for Semantic Segmentation of Remote Sensing Images},
    journal = {Remote Sensing},
    volume = {15},
    year = {2023},
    number = {24},
    article-number = {5644},
    url = {https://www.mdpi.com/2072-4292/15/24/5644},
    issn = {2072-4292},
    doi = {10.3390/rs15245644}
}
```

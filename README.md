# PRIMIS: PRIvacy-preserving Medical Image Sharing 

This repository serves as a gateway to the primary repository that contains the official PyTorch implementation of our work.

## Overview

Our aim is to design a privacy-preserving data-sharing mechanism that allows medical images to be stored as encoded and obfuscated representations in the public domain without revealing any useful or recoverable content from the images. In tandem, we aim to provide authorized users with compact private keys that could be used to reconstruct the corresponding images. 

## Methodology

Our approach involves utilizing a neural auto-encoder. The convolutional filter outputs are passed through sparsifying transformations to produce multiple compact codes. Each code is responsible for reconstructing different attributes of the image. The key privacy-preserving element in this process is obfuscation through the use of specific pseudo-random noise. When applied to the codes, it becomes computationally infeasible for an attacker to guess the correct representation for all codes, thereby preserving the privacy of the data. 

## Main Repository

The complete code, along with more detailed documentation, is available in the main repository hosted by my co-author. We encourage you to visit [PRIMIS Official Repository](https://github.com/sssohrab/PRIMIS) for our implementation, including setup guidelines, usage cases, and support information.


## Citation

If you find our work useful in your research, please consider citing our paper. The bibtex entry is provided below:

```bibtex
@article{shiri2023primis,
  title={PRIMIS: Privacy-Preserving Medical Image Sharing via Deep Sparsifying Transform Learning with Obfuscation},
  author={Shiri, Isaac and Razeghi, Behrooz and Ferdowsi, Sohrab and Salimi, Yazdan and G{\"u}nd{\"u}z, Deniz and Teodoro, Douglas and oloshynovskiy, Slava and Zaidi, Habib},
  journal={},
  volume={},
  pages={},
  year={2023},
  publisher={Elsevier}
}

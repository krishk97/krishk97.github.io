---
title: "F?D: On understanding the role of deep feature spaces on face generation evaluation"
collection: publications
permalink: /publication/causal-fid
excerpt: "A causal analysis showing how different facial attributes and distortions to semantic regions impact the Fréchet distance across several popular deep feature spaces" 
date: 2023-5-31 
imageurl: '/images/publications/causal-fid/counterfactuals-attrs.png' 
paperurl: '/files/causal-fid.pdf'
conference: CVPRW 2024
citation: '<strong>K. Kabra</strong>, G. Balakrishnan (2023). &quot;F?D: On understanding the role of deep feature spaces on face generation evaluation&quot; <i>arXiv preprint</i> arXiv:2305.20048.'
--- 

<div style="text-align:center;">
  <p style="color:gray">Poster at Responsible Generative AI Workshop, CVPR 2024</p>

  <strong><a href="https://krishk97.github.io/"> Krish Kabra</a><sup>1</sup></strong>, <a href="https://www.guhabalakrishnan.com/">Guha Balakrishnan</a><sup>1,*</sup><br>

  <sup>1</sup>Rice University<br>
  <sup>*</sup>Corresponding author: guha@rice.edu<br>
  <br>
</div>

[<i class="ai ai-arxiv-square ai-fw"></i> arXiv](https://arxiv.org/abs/2210.04868){:.btn .btn-dark style="text-decoration: none;"} [<i class="fas fa-fw fa-file-pdf"></i> PDF](/files/causal-fid.pdf){:.btn .btn-dark style="text-decoration: none;"}
{: style="text-align: center"}

<center><img src = '/images/publications/causal-fid/causal-analysis-fid-overview-v5.png'></center>

## Abstract 
<p style="text-align:justify;">
Perceptual metrics, like the Fréchet Inception Distance (FID), are widely used to assess the similarity between synthetically generated and ground truth (real) images. The key idea behind these metrics is to compute errors in a deep feature space that captures perceptually and semantically rich image features. Despite their popularity, the effect that different deep features and their design choices have on a perceptual metric has not been well studied. In this work, we perform a causal analysis linking differences in semantic attributes and distortions between face image distributions to Fréchet distances (FD) using several popular deep feature spaces. A key component of our analysis is the creation of synthetic counterfactual faces using deep face generators. Our experiments show that the FD is heavily influenced by its feature space's training dataset and objective function. For example, FD using features extracted from ImageNet-trained models heavily emphasize hats over regions like the eyes and mouth. Moreover, FD using features from a face gender classifier emphasize hair length more than distances in an identity (recognition) feature space. Finally, we evaluate several popular face generation models across feature spaces and find that StyleGAN2 consistently ranks higher than other face generators, except with respect to identity (recognition) features. This suggests the need for considering multiple feature spaces when evaluating generative models and using feature spaces that are tuned to nuances of the domain of interest.
</p>

## Citation 
```bibitex
@article{kabra2023fd,  
  title={F?D: On understanding the role of deep feature spaces on face generation evaluation}, 
  author={Kabra, Krish and Balakrishnan, Guha},
  journal={arXiv preprint arXiv:2305.20048},
  year={2023}
}
```

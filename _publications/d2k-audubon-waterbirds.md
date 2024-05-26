---
title: "Deep object detection for waterbird monitoring using aerial imagery"
collection: publications
permalink: /publication/d2k-audubon-waterbirds
excerpt: "An automatic annotation framework that leverages LLMs and VLMs to propose and label various attributes for a domain." 
date: 2022-12-12
conference: ICMLA 2022
link: 'https://ieeexplore.ieee.org/abstract/document/10069986/'
imageurl: '/images/publications/thumbnail-d2k-audubon-waterbirds.png' 
paperurl: '/files/audubon-waterbirds.pdf'
github: https://github.com/RiceD2KLab/Audubon_F21
citation: '<strong>K. Kabra</strong>, A. Xiong, W. Li, M. Luo, W. Lu, R. Garcia, D. Vijay, J. Yu, M. Tang, T. Yu, H. Arnold, A. Vallery, R. Gibbons, A. Barman (2022). &quot;Deep object detection for waterbird monitoring using aerial imagery&quot; <i>2022 21st IEEE International Conference on Machine Learning and Applications (ICMLA)</i>, Nassau, Bahamas, 2022, pp. 455-460, doi: 10.1109/ICMLA55696.2022.00073.'
---

<div style="text-align:center;">
  <strong><a href="https://krishk97.github.io/">Krish Kabra</a><sup>1,†</sup></strong>, Alexander Xiong<sup>1,†</sup>, Wenbin Li<sup>1,†</sup>, Minxuan Luo<sup>1</sup>, William Lu<sup>1</sup>, Raul Garcia<sup>1</sup>, Dhananjay Vijay<sup>1</sup>, Jiahui Yu<sup>1</sup>, Maojie Tang<sup>1</sup>, Tianjiao Yu<sup>1</sup>, Hank Arnold<sup>2</sup>, Anna Vallery<sup>2</sup>, Richard Gibbons<sup>3</sup>, <a href="https://profiles.rice.edu/faculty/arko-barman">Arko Barman</a><sup>1</sup><br>
  <br>
  <sup>1</sup>Rice University<br>
  <sup>2</sup>Houston Audubon Society<br>
  <sup>2</sup>American Bird Conservancy<br>
  <sup>†</sup>Denotes equal contribution
  <sup>*</sup>Corresponding author: kk80@rice.edu<br>
  <br>
</div>

[<i class="fas fa-fw fa-link"></i> Article](https://ieeexplore.ieee.org/abstract/document/10069986/){:.btn .btn-dark style="text-decoration: none;"} [<i class="ai ai-arxiv-square ai-fw"></i> arXiv](https://arxiv.org/abs/2210.04868){:.btn .btn-dark style="text-decoration: none;"} [<i class="fas fa-fw fa-file-pdf"></i> PDF](files/audubon-waterbirds.pdf){:.btn .btn-dark style="text-decoration: none;"} [<i class="fab fa-fw fa-github"></i> Code](https://github.com/RiceD2KLab/Audubon_F21){:.btn .btn-dark style="text-decoration: none;"} 
{: style="text-align: center"}

<center><img src = '/images/publications/d2k-audubon-waterbirds/visual_results.png'></center>

## Abstract
<p style="text-align:justify;">
  Monitoring of colonial waterbird nesting islands is essential to tracking waterbird population trends, which are used for evaluating ecosystem health and informing conservation management decisions. Recently, unmanned aerial vehicles, or drones, have emerged as a viable technology to precisely monitor waterbird colonies. However, manually counting waterbirds from hundreds, or potentially thousands, of aerial images is both difficult and time-consuming. In this work, we present a deep learning pipeline that can be used to precisely detect, count, and monitor waterbirds using aerial imagery collected by a commercial drone. By utilizing convolutional neural network-based object detectors, we show that we can detect 16 classes of waterbird species that are commonly found in colonial nesting islands along the Texas coast. Our experiments using Faster R-CNN and RetinaNet object detectors give mean interpolated average precision scores of 67.9% and 63.1% respectively.
</p>

## Press
* [Rice University News](https://d2k.rice.edu/news/theyre-data-scientists-not-birdwatchers)

## Citation
```bibitex
@inproceedings{kabra2022deep,
  title={Deep object detection for waterbird monitoring using aerial imagery},
  author={Kabra, Krish and Xiong, Alexander and Li, Wenbin and Luo, Minxuan and Lu, William and Yu, Tianjiao and Yu, Jiahui and Singh, Dhananjay and Garcia. Raul and Tang, Maojie and others},
  booktitle={2022 21st IEEE International Conference on Machine Learning and Applications (ICMLA)},
  pages={455--460},
  year={2022},
  organization={IEEE}
}
```
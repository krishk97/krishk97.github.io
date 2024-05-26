---
title: "Diverse R-PPG: Camera-Based Heart Rate Estimation for Diverse Subject Skin-Tones and Scenes"
collection: publications
permalink: /publication/diverse-rppg
excerpt: "A novel algorithm to mitigate skin tone bias for remote heart rate estimation."
date: 2020-10-24
conference: arXiv
imageurl: '/images/publications/diverse-rppg-video-demo.gif'
paperurl: '/files/Diverse-RPPG.pdf'
link: 'https://visual.ee.ucla.edu/diverse_rppg.htm'
citation: 'P. Chari, <strong>K. Kabra</strong>, D. Karinca, S. Lahiri, D. Srivastava, K. Kulkarni, T. Chen, M. Cannesson, L. Jalilian, A. Kadambi (2020). &quot;Diverse R-PPG: Camera-Based Heart Rate Estimation for Diverse Subject Skin-Tones and Scenes.&quot; <i>arXiv preprint</i> arXiv:2010.12769.'
---

<div style="text-align:center;">
    Pradyumna Chari<sup>1</sup>, <strong>Krish Kabra<sup>1</sup></strong>, Doruk Karinca<sup>1</sup>, Soumyarup Lahiri<sup>1</sup>, Diplav Srivastava<sup>1</sup>, Kimaya Kulkarni<sup>1</sup>, Tianyuan Chen<sup>1</sup>, Maxime Cannesson<sup>2</sup>, Laleh Jalilian<sup>2</sup>, Achuta Kadambi<sup>1,3,*</sup><br>
    <br>
    <sup>1</sup>Department of Electrical and Computer Engineering, UCLA, Los Angeles, California 90095, USA<br>
    <sup>2</sup>Department of Anesthesiology and Perioperative Medicine, UCLA, Los Angeles, California 90095, USA<br>
    <sup>3</sup>California NanoSystems Institute, University of California, Los Angeles, California 90095, USA<br>
    <sup>*</sup>Corresponding author: achuta@ee.ucla.edu<br>
    <br>
</div>

[<i class="fas fa-fw fa-link"></i> Website](https://visual.ee.ucla.edu/diverse_rppg.htm){:.btn .btn-dark style="text-decoration: none;"} [<i class="ai ai-arxiv-square ai-fw"></i> arXiv](https://arxiv.org/abs/2010.12769){:.btn .btn-dark style="text-decoration: none;"} [<i class="fab fa-fw fa-file-pdf"></i> PDF](/files/Diverse-RPPG.pdf){:.btn .btn-dark style="text-decoration: none;"} 
{: style="text-align: center"}

<center><img src = '/images/publications/diverse-rppg-video-demo.gif'></center>

## Abstract
<p style="text-align:justify;">
    Heart rate (HR) is an essential clinical measure for the assessment of cardiorespiratory instability. Since communities of color are disproportionately affected by 
    both COVID-19 and cardiovascular disease, there is a pressing need to deploy contactless HR sensing solutions for high-quality telemedicine evaluations. Existing
    computer vision methods that estimate HR from facial videos exhibit biased performance against dark skin tones. We present a novel physics-driven algorithm that 
    boosts performance on darker skin tones in our reported data. We assess the performance of our method through the creation of the first telemedicine-focused remote 
    vital signs dataset, the VITAL dataset. 432 videos (~864 minutes) of 54 subjects with diverse skin tones are recorded under realistic scene conditions with 
    corresponding vital sign data. Our method reduces errors due to lighting changes, shadows, and specular highlights and imparts unbiased performance gains across 
    skin tones, setting the stage for making medically inclusive non-contact HR sensing technologies a viable reality for patients of all skin tones.
</p>

## Citation
```bibitex
@inproceedings{chari2020-diverse-rppg,
    title={Diverse R-PPG: Camera-Based Heart Rate Estimation for Diverse Subject Skin-Tones and Scenes}, 
    author={Pradyumna Chari and Krish Kabra and Doruk Karinca and Soumyarup Lahiri and Diplav Srivastava and Kimaya Kulkarni and Tianyuan Chen and Maxime Cannesson and Laleh Jalilian and Achuta Kadambi},
    year={2020}, 
    eprint={2010.12769},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}
```
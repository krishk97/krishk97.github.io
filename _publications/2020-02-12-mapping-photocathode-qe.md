---
title: "Mapping photocathode quantum efficiency with ghost imaging"
collection: publications
permalink: /publication/2020-02-12-mapping-photocathode-qe
excerpt: "A ghost imaging framework for measuring the photocathode quantum efficiency map."
date: 2020-02-12
journal: 'Physical Review Accelerators and Beams'
imageurl: '/images/publications/map-QE-egi-thumb.png'
paperurl: '/files/mapping-photocathode-QE.pdf'
link: 'https://doi.org/10.1103/PhysRevAccelBeams.23.022803'
citation: '<strong>K. Kabra</strong>, S. Li, F. Cropp, Thomas J. Lane, P. Musumeci, and D. Ratner (2020). &quot;Mapping photocathode quantum efficiency with ghost imaging.&quot; <i>Phys. Rev. Accel. Beams, 23</i>, 022803. doi:10.1103/PhysRevAccelBeams.23.022803'
---

<div style="text-align:center;">
  <strong>Krish Kabra<sup>1,2,*</sup></strong>, Siqi Li<sup>3,+</sup>, Fredrick Cropp<sup>1</sup>, Thomas J. Lane<sup>3</sup>, Pietro Musumeci<sup>1</sup>, Daniel Ratner<sup>3</sup><br>
  <br>
  <sup>1</sup>Department of Physics and Astronomy, UCLA, Los Angeles, California 90095, USA<br>
  <sup>2</sup>Department of Electrical Engineering, UCLA, Los Angeles, California 90095, USA<br>
  <sup>3</sup>SLAC National Accelerator Laboratory, Menlo Park, California, 94025, USA<br>
  <sup>*</sup>Corresponding author: krish97@g.ucla.edu<br>
  <sup>+</sup>Corresponding author: siqili@slac.stanford.edu<br>
  <br>
</div>

[<i class="fas fa-fw fa-link"></i> Article](https://doi.org/10.1103/PhysRevAccelBeams.23.022803){:.btn .btn-dark style="text-decoration: none;"} [<i class="fas fa-fw fa-file-pdf"></i> PDF](/files/mapping-photocathode-QE.pdf){:.btn .btn-dark style="text-decoration: none;"}
{: style="text-align: center"}

<center><img src = '/images/publications/map-QE-egi-thumb.png'></center>

<p style="text-align:justify;">
  <i>QE map reconstructions. The top row shows example laser profiles used to generate the QE maps seen on the bottom row. 
  Left: Ground truth QE map obtained by raster scan. Middle: reconstruction using the random mask dataset. 
  Right: reconstruction using the jitter dataset. The random and jitter datasets successfully reconstruct the hot spot seen 
  in the upper right corner of the ground truth</i>
</p>

## Abstract
<p style="text-align:justify;">
  Measuring the quantum efficiency (QE) map of a photocathode injector typically requires laser scanning, an invasive operation that involves 
  modifying the injector laser focus and rastering the focused laser spot across the photocathode surface. Raster scanning interrupts normal 
  operation and takes considerable time to setup. In this paper, we demonstrate a novel method of measuring the QE map using a ghost imaging 
  framework that correlates the injector laser spatial variation over time with the total charge yield. Ghost imaging enables passive, real-time
  monitoring of the QE map without manually modifying the injector laser or interrupting injector operation. We first demonstrate the method at 
  the UCLA Pegasus photoinjector with the help of a digital micromirror device (DMD) and a piezoelectric mirror to increase our control of the 
  overall transverse variance of the illumination profile. The reconstruction algorithm parameters are fine-tuned using simulations and the results
  are validated against the ground truth map acquired using the traditional rastering method. Finally, we apply the technique to data acquired 
  parasitically from the LCLS photoinjector, showing the feasibility of this method to retrieve a QE map without interrupting normal operation.
</p>

## Citation
```bibitex
@article{kabra2020-mapping-photocathode-qe,
  title = {Mapping photocathode quantum efficiency with ghost imaging},
  author = {Kabra, K. and Li, S. and Cropp, F. and Lane, Thomas J. and Musumeci, P. and Ratner, D.},
  journal = {Phys. Rev. Accel. Beams},
  volume = {23},
  issue = {2},
  pages = {022803},
  numpages = {9},
  year = {2020},
  month = {Feb},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevAccelBeams.23.022803},
  url = {https://link.aps.org/doi/10.1103/PhysRevAccelBeams.23.022803}
}
```
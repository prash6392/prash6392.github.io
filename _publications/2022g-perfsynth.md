---
title: "Facial Animation with Disentangled Identity and Motion using Transformers"
collection: publications
permalink: /publication/2022g-perfsynth
teaser: /images/perf2022.png
excerpt: We propose a 3D+time framework for modeling dynamic sequences of 3D facial shapes, representing realistic non-rigid motion during a performance. [[Project Page]](https://studios.disneyresearch.com/2022/09/13/facial-animation-with-disentangled-identity-and-motion-using-transformers/)<br><br>
date: 2022-09-13
venue: 'ACM/Eurographics Symposium on Computer Animation'
bibtex: "
@article{https://doi.org/10.1111/cgf.14641, <br>
author = {Chandran, Prashanth and Zoss, Gaspard <br> and Gross, Markus and Gotardo, Paulo and Bradley, Derek},<br>
title = {Facial Animation with Disentangled Identity <br> and Motion using Transformers},
journal = {Computer Graphics Forum}, <br>
volume = {41},<br>
number = {8},<br>
pages = {267-277},<br>
doi = {https://doi.org/10.1111/cgf.14641},<br>
year = {2022}<br>
}
"
---

**Abstract**
<p>
We propose a 3D+time framework for modeling dynamic sequences of 3D facial shapes, representing realistic non-rigid motion during a performance. Our work extends neural 3D morphable models by learning a motion manifold using a transformer architecture. More specifically, we derive a novel transformer-based autoencoder that can model and synthesize 3D geometry sequences of arbitrary length. This transformer naturally determines frame-to-frame correlations required to represent the motion manifold, via the internal self-attention mechanism. Furthermore, our method disentangles the constant facial identity from the time-varying facial expressions in a performance, using two separate codes to represent neutral identity and the performance itself within separate latent subspaces. Thus, the model represents identity-agnostic performances that can be paired with an arbitrary new identity code and fed through our new identity-modulated performance decoder; the result is a sequence of 3D meshes for the performance with the desired identity and temporal length. We demonstrate how our disentangled motion model has natural applications in performance synthesis, performance retargeting, key-frame interpolation and completion of missing data, performance denoising and retiming, and other potential applications that include full 3D body modeling.
</p>

[Project Page](https://studios.disneyresearch.com/2022/09/13/facial-animation-with-disentangled-identity-and-motion-using-transformers/)

**Bibtex:** 
<pre>
@article{https://doi.org/10.1111/cgf.14641, 
author = {Chandran, Prashanth and Zoss, Gaspard and Gross, Markus and Gotardo, Paulo and Bradley, Derek},
title = {Facial Animation with Disentangled Identity and Motion using Transformers},
journal = {Computer Graphics Forum},
volume = {41},
number = {8},
pages = {267-277},
doi = {https://doi.org/10.1111/cgf.14641},
year = {2022}
}
</pre>
{: .notice}
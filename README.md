<!-- PROJECT SHIELDS -->
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## [Neural Colour Correction for Indoor 3D Reconstruction Using RGB-D Data](https://www.mdpi.com/1424-8220/24/13/4141)  
[Tiago Madeira](https://www.researchgate.net/profile/Tiago-Madeira)<sup>1,2</sup>, [Miguel Oliveira](https://www.researchgate.net/profile/Miguel-Oliveira-17)<sup>1,3</sup>, [Paulo Dias](https://www.researchgate.net/profile/Paulo-Dias-6)<sup>1,2</sup><br>
<sup>1</sup>Institute of Electronics and Informatics Engineering of Aveiro (IEETA), University of Aveiro, Portugal  
<sup>2</sup>Department of Electronics, Telecommunications and Informatics (DETI), University of Aveiro, Portugal  
<sup>3</sup>Department of Mechanical Engineering (DEM), University of Aveiro, Portugal

<img src='https://www.mdpi.com/sensors/sensors-24-04141/article_deploy/html/images/sensors-24-04141-g001.png'/>
<img src='https://www.mdpi.com/sensors/sensors-24-04141/article_deploy/html/images/sensors-24-04141-g003.png'/>

## Abstract

With the rise in popularity of different human-centred applications using 3D reconstruction data, the problem of generating photo-realistic models has become an important task. In a multiview acquisition system, particularly for large indoor scenes, the acquisition conditions will differ along the environment, causing colour differences between captures and unappealing visual artefacts in the produced models. We propose a novel neural-based approach to colour correction for indoor 3D reconstruction. It is a lightweight and efficient approach that can be used to harmonize colour from sparse captures over complex indoor scenes. Our approach uses a fully connected deep neural network to learn an implicit representation of the colour in 3D space, while capturing camera-dependent effects. We then leverage this continuous function as reference data to estimate the required transformations to regenerate pixels in each capture. Experiments to evaluate the proposed method on several scenes of the MP3D dataset show that it outperforms other relevant state-of-the-art approaches.

## Citation

If you use **NeurA** in your work, please cite:

```bibtex
@Article{10.3390/s24134141,
AUTHOR = {Madeira, Tiago and Oliveira, Miguel and Dias, Paulo},
TITLE = {Neural Colour Correction for Indoor 3D Reconstruction Using RGB-D Data},
JOURNAL = {Sensors},
VOLUME = {24},
YEAR = {2024},
NUMBER = {13},
ARTICLE-NUMBER = {4141},
DOI = {10.3390/s24134141}
}
```

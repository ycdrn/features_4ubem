# Deep Learning-Based WWR and Floor Count Extraction from Façade Images to Improve UBEM

[Ayca Duran](https://systems.arch.ethz.ch/ayca-duran), [Panagiotis Karapiperis](https://www.linkedin.com/in/panagiotis-karapiperis-ethz/), [Christoph Waibel](https://systems.arch.ethz.ch/christoph-waibel), [Arno Schlueter](https://systems.arch.ethz.ch/arno-schlueter)

[[ Paper ]](tba) – CISBAT 2025

## Table of Contents
1. [Abstract](#abstract)
2. [Citation](#citation)

## Abstract
Urban Building Energy Modeling (UBEM) enables the energy performance evaluation of entire neighborhoods and cities, playing an important role in achieving net-zero carbon objectives. However, bottom-up UBEM frameworks rely on large amounts of input data, such as floor counts, window-to-wall (WWR) ratio, and material constructions, which are often difficult to obtain or missing from open data sources like OpenStreetMap. This study proposes a deep-learning (DL)-based computer vision workflow to automate the extraction of two features, namely (1) floor count and (2) window-to-wall ratio, from street-level façade imagery. The extracted features are integrated into the UBEM platform City Energy Analyst to quantify the differences in simulated annual energy demand between the standard model, the proposed workflow, and the ground truth. The method is applied to a district in Zurich, Switzerland, which includes 24 buildings. The UBEM model with the DL-predicted floor counts and WWR underestimates the total energy demand by 9% relative to the model using true values, whereas the model with default values underestimates it by  31%. Although issues such as partial occlusions and image perspective reduce accuracy, the proposed method demonstrates a scalable approach to reduce manual data collection and improve urban-scale energy assessments.

## Citation
If using our dataset/model, please cite us as follows:
```bibtex
@article{DURAN2025112310,
  title     = {Deep Learning-Based WWR and Floor Count Extraction from Façade Images to Improve UBEM},
  journal   = {Journal of Physics: Conference Series},
  volume    = {tba},
  pages     = {tba},
  year      = 2025,
  issn      = {tba},
  doi       = {tba},
  author    = {Ayca Duran and Panagiotis Karapiperis and Christoph Waibel and Arno Schlueter}
}
```

# geoprompt-mvs
Official repository for the paper "Reliability-Aware Training-Free Geometric Prompting for Frozen MVS".

The source code will be released upon publication.

## Quantitative Experimental Results

**GeoPrompt-MVS** is a training-free geometric prompting framework that enables frozen multi-view stereo (MVS) models to leverage sparse metric depth observations for improved depth estimation. It assesses prompt reliability based on cross-view geometric consistency and matching evidence, integrating reliable geometric cues while mitigating the impact of noisy or inconsistent observations. Extensive evaluations across five benchmarks—KITTI, ScanNet, ETH3D, DTU, and T&T—demonstrate the effectiveness of GeoPrompt-MVS in improving depth estimation without additional model training. The figure below presents an overview of our approach and selected experimental results.

![Selected GeoPrompt-MVS method illustration and experimental results](assets/quantitative.png)

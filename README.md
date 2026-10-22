# geoprompt-mvs
Official implementation of "Reliability-Aware Training-Free Geometric Prompting for Frozen MVS".

The code will be made publicly available upon publication.

## Method Overview and Experimental Results

The figure compares a frozen MVSAnywhere baseline with **GeoPrompt-MVS** on a representative scene. GeoPrompt-MVS adds depth prompts to posed RGB images and applies reliability-aware prompting (RASA, CAPC, and AGPF) before passing them to the frozen model. The reported error in this example decreases from 9.12% to 2.42%. The chart compares depth accuracy across KITTI, ScanNet, ETH3D, DTU, and T&T.

![GeoPrompt-MVS prompting pipeline, depth comparison, and depth accuracy chart](assets/quantitative.png)

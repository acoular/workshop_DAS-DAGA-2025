[![DOI](https://zenodo.org/badge/926471449.svg)](https://doi.org/10.5281/zenodo.15112155)

# Acoular Workshop – DAS | DAGA 2025

<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <img src="https://github.com/acoular/workshop_DAS-DAGA-2025/img/Acoular_logo.png" alt="Acoular" style="height: 100px; width: auto;">
  <img src="https://github.com/acoular/workshop_DAS-DAGA-2025/img/TU-lang.png" alt="TU" style="height: 100px; width: auto;">
  <img src="https://github.com/acoular/workshop_DAS-DAGA-2025/img/DAGA_logo.png" alt="DAGA" style="height: 100px; width: auto;">
</div>

Official collection of Jupyter notebooks, presented at the DAS|DAGA 2025 conference during the session: 

**Acoular Workshop: Accessible and Reproducible Microphone Array Signal Processing with Python**

Session details: [DAS|DAGA 2025](https://app2025.daga-tagung.de/konferenz?session=21)

## Schedule

* 08:40 **Accessible and Reproducible Microphone Array Signal Processing with Python**
* 09:00 **Getting Started with Acoular**
* 09:20 **Generating Synthetic Sound Pressure Time Datasets of Multicopter Drone Fly-bys**
* 09:40 **Beamforming in the Time Domain with Moving Sources**
* 10:00 **Coffee Break**
* 10:20 **An Interactive Tutorial on Advanced Microphone Array Methods for Acoustic Source Mapping**
* 10:40 **Modelling Flow Environments for the Correction of Aeroacoustic Microphone Array Measurements**
* 11:00 **Acoustic Data Acquisition and Processing in Python using a MEMS Microphone Array**
* 11:20 **Comparison of Embedded Hardware Platforms for Optimized Machine Learning-Based Acoustic Imaging**    

## Installation

Installation with `conda`, `mamba` or `micromamba`:

* install dependencies including `nbclassic` to use the classic notebook interface

```bash
conda env create -f env.yml
```

* if you require an explicit installation including builds, use the following command:

```bash
conda env create -f env_explicit.yml
```

Run the notebooks (from the repository root):

```bash
conda run -n acoular-workshop-das-daga-25 jupyter nbclassic
```

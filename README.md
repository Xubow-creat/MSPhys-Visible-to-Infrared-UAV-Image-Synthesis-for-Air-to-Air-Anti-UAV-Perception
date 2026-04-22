# MSPhys: Physics-Informed Multi-Scale Visible-to-Infrared UAV Image Synthesis

<p align="center">
  <img src="assets/teaser.png" alt="MSPhys teaser" width="88%">
</p>

<p align="center">
  <em>
    A physics-informed multi-scale framework for visible-to-infrared UAV image synthesis
    in air-to-air anti-UAV scenarios.
  </em>
</p>

---

## Overview

Infrared UAV perception plays an important role in air-to-air anti-UAV applications because of its passive sensing capability and robustness under low-visibility conditions. However, collecting large-scale, high-quality infrared UAV data is expensive and difficult, especially in real air-to-air environments.

To address this problem, we propose **MSPhys**, a physics-informed multi-scale framework for visible-to-infrared UAV image synthesis. The framework is designed to improve:

- thermal-physical plausibility,
- structural fidelity,
- robustness to scale variation,
- generation quality in complex backgrounds.

MSPhys integrates physics-aware feature modulation, multi-scale representation learning, and deformable adversarial discrimination to generate infrared UAV images that are more suitable for downstream anti-UAV perception tasks.

---

## Highlights

- Physics-informed visible-to-infrared UAV image synthesis
- Multi-scale adaptive modeling for complex air-to-air scenes
- Improved target-background separability and structural preservation
- Practical support for infrared UAV data generation and downstream detection

---

## Framework

<p align="center">
  <img src="assets/framework.png" alt="MSPhys framework" width="90%">
</p>

**MSPhys** mainly includes:

- **Phys-AdaIN+** for physics-aware adaptive feature modulation,
- **dual-path encoding with LoG enhancement** for improved structure and edge preservation,
- **DMSC** for deformable multi-scale sparse cross-modal alignment,
- **DMDisc** for robust multi-scale adversarial supervision.

---

## Visual Results

<p align="center">
  <img src="assets/visual_comparison.png" alt="Visual comparison" width="90%">
</p>

The proposed method shows strong performance in visual fidelity, contour preservation, target-background discrimination, and robustness under challenging air-to-air UAV scenarios.

---

## TeV-Oriented Physical Analysis

<p align="center">
  <img src="assets/tev_visualization.png" alt="TeV visualization" width="85%">
</p>

To better understand the physical plausibility of the generated infrared images, we further present TeV-oriented visualization results, including temperature-related structure, emissivity-related characteristics, and environmental irradiance consistency.

---

## Repository Status

This repository is currently in the **project-introduction stage**.

At this stage, it mainly provides:

- project overview,
- selected figures from the paper,
- high-level description of the method,
- planned release information.

**The full source code, pretrained models, and additional reproducibility materials will be released after the paper is accepted/published.**

---

## Paper Information

**Title**  
*Soft Computing-Driven Infrared UAV Image Synthesis from Visible Light: Leveraging Multi-Scale Adaptation and Physical Consistency for Real-World Anti-UAV Applications*

**Status**  
Under review

---

## Planned Release

After acceptance/publication, this repository will be updated with:

- full training and inference code,
- pretrained model checkpoints,
- environment configuration files,
- reproduction instructions,
- additional implementation details and supplementary materials.

---

## Notes

This repository will be updated in stages.  
The current version is intended to provide a concise and readable introduction to the project.  
More materials will be released after the review/publication process.

---

## Citation

Citation information will be added after the paper is accepted/published.

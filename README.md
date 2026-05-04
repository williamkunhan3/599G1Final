# 599G1 Final Project — Localized Consistency Optimization for AI-Generated E-Commerce Video

This repository contains the manuscript, code, and model artifacts for our final project, a method for fine-tuning video diffusion models
to preserve product fidelity in AI-generated short-form commerce video.

## Repository Contents

| Path / File           | Description                                                                 |
| --------------------- | --------------------------------------------------------------------------- |
| `manuscript.pdf`      | Full paper describing the method, experiments, and results.                 |
| `Wan_Finetuning/`     | Dataset preprocessing pipeline and training/inference scripts for Wan2.2.   |
| `diffsynth.zip`       | DiffSynth-Studio engine (packaged) used as the underlying diffusion backend.|
| `model training/inference`               | Packaged wheel for model training and inference.                            |

## Quick Start

1. **Read the paper.** Start with `manuscript.pdf` for the motivation, method, and results.
2. **Set up the engine.** Unzip `diffsynth.zip` and install the wheel:

# Computer Vision – Image Generation

A multimodal computer-vision project exploring **EEG-based visual representation learning and image generation** using PyTorch and StyleGAN-ADA.

## Overview

The project implements a pipeline for learning visual representations from EEG signals and using those representations for synthetic image generation and evaluation.

**Core workflow:**

EEG Signals → Learned EEG Representation → StyleGAN-ADA → Synthetic Visual Data

The repository contains two StyleGAN-ADA experiments and supporting EEG–image representation-learning code.

## Project Components

### 1. EEGStyleGAN-ADA_CVPR40
StyleGAN-ADA based image-generation pipeline using learned EEG feature representations.

Includes:
- EEG feature checkpoints
- StyleGAN-ADA training and generation
- Dataset preparation and preprocessing
- Image generation and visualization
- Evaluation and metric computation

### 2. EEGStyleGAN-ADA_ThoughtViz
A second StyleGAN-ADA experiment using the ThoughtViz dataset, following the same EEG-to-visual generation workflow.

Includes:
- EEG feature representations
- StyleGAN-ADA training and generation
- Evaluation utilities
- Visualization and experiment scripts

### 3. Image2EEG
Supporting representation-learning implementation for learning relationships between visual inputs and EEG representations.

Includes:
- PyTorch training pipelines
- EEG/image encoders
- Contrastive and triplet-based objectives
- Linear probing and retrieval evaluation
- Visualization and analysis utilities

## Technical Approach

- **Deep Learning:** PyTorch
- **Image Generation:** StyleGAN-ADA
- **Representation Learning:** EEG–image alignment and learned feature representations
- **Training:** CNN/LSTM-based EEG modeling, contrastive/triplet objectives
- **Evaluation:** Image-generation metrics, retrieval/classification evaluation, and visual analysis
- **GPU:** CUDA-enabled training and inference

## Key Outcome

Developed an end-to-end research pipeline connecting **EEG-derived representations with generative visual modeling**, combining representation learning, StyleGAN-ADA image generation, and quantitative/qualitative evaluation.

## Repository Scope

This repository contains the core training, generation, representation-learning, evaluation, and visualization code used in the project. Large raw datasets and unnecessary generated artifacts are intentionally excluded.
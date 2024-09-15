# Differentiating and Specialization in Language Models via the Refined Local Learning Coefficient

This repository contains extra data for the paper "Differentiating and Specialization in Language Models via the Refined Local Learning Coefficient" by [AUTHOR NAMES BLOCKED FOR PEER REVIEW], published in [PUBLICATION DETAILS BLOCKED FOR PEER REVIEW].

## Abstract

We introduce refined variants of the Local Learning Coefficient (LLC), a measure of model complexity and degeneracy in the loss landscape geometry, to study the development of individual components in transformer language models during training. By applying these Refined Local Learning Coefficients (rLLCs) to a two-layer attention-only transformer trained on a subset of the Pile, we gain novel insights into the progressive differentiation and specialization of attention heads. Our methodology reveals the emergence of different types of attention heads, data-specific specialization, and a universal pattern of increasing then decreasing rLLCs potentially linked to functional disentanglement. These findings highlight rLLCs as a principled tool for understanding neural network development, grounded in singular learning theory.

## Repository Structure

- `figures/`: Extra figures not included in the paper

## Data

We use a subset of the Pile dataset for training and evaluation. The data preprocessing steps are described in detail in the `data/README.md` file.

## Results

Key results and figures can be reproduced using the notebooks in the `notebooks/` directory. Precomputed results are available in the `results/` directory.

## Citation

If you use this code or data in your research, please cite our paper:

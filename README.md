# Differentiating and Specialization in Language Models via the Refined Local Learning Coefficient

This repository contains extra data for the paper "Differentiating and Specialization in Language Models via the Refined Local Learning Coefficient" by [AUTHOR NAMES BLOCKED FOR PEER REVIEW], published in [PUBLICATION DETAILS BLOCKED FOR PEER REVIEW].

## Abstract

> We introduce refined variants of the Local Learning Coefficient (LLC), a measure of model complexity grounded in singular learning theory, to study the development of internal structure in transformer language models during training. By applying these \textit{refined LLCs} (rLLCs) to individual components of a two-layer attention-only transformer, we gain novel insights into the progressive differentiation and specialization of attention heads. Our methodology reveals how attention heads differentiate into distinct functional roles over the course of training, analyzes the types of data these heads specialize to process, and discovers a previously unidentified multigram circuit. These findings demonstrate that rLLCs provide a principled, quantitative toolkit for \textit{developmental interpretability}, which aims to understand models through their evolution across the learning process. More broadly, this work takes a step towards establishing the correspondence between data distributional structure, geometric properties of the loss landscape, learning dynamics, and emergent computational structures in neural networks.

## Repository Structure

- `figures/`: Figures from the paper + some extras that didn't make the cut.
- `per-token-data/`: Raw data of tokens in context generated using the procedure detailed in Appendix B.
- `per-token-samples/`: HTML presentation of tokens in context.
- `per-token-analysis/`: Results of analyzing these samples in terms of induction patterns, Dyck patterns, skip n-grams, and n-grams.



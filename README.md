# PCA-from-Scratch

This project implements Principal Component Analysis (PCA) from scratch using NumPy-only and Singular Value Decomposition (SVD).

The goal is to understand PCA not as a black-box dimensionality reduction tool, but as a projection onto the directions of maximum variance.

## Key Idea

Given a N x D centered data matrix A,

X = UΣVᵀ

the right singular vectors V indicate the principal directions with maximum variance, and singular values Σ indicate how much the vectors capture variance.

## What I Implemented

- Data centering
- PCA with SVD
- Singular vectors visualization
- Data projection to principal components
- Data reconstruction procedure
- Explained variance ratio

## Main Result

PCA finds orthogonal directions that capture the maximum variance of the data. By projecting data onto the top principal components, we can reduce dimensionality while preserving the most important structure.

![comparison_original_reconstruction](./results/comparison_original_reconstruction.png)

## Tech Stack

Numpy, Matplotlib

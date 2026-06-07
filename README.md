# 540 Machine Learning Workshop

This project aims at creating an instructional, and interactive series 
to teach machine learning fundamentals for any role.

## Table of Contents
1. Introduction to Python \& Jupyter Notebooks
2. Concept Learning \& k-Nearest Neighbor
3. Linear Models \& Support Vector Machines
4. Decision Trees
5. Ensemble Models
6. Performance Evaluation \& Experimental Design Techniques
7. Parametric Models, Hyper-parameter \& Model Selection
8. Dimensionality Reduction
9. Unsupervised Learning \& Clustering
10. Artificial Neural Networks
11. Deep Learning
12. Reinforcement Learning

## Requirements

- Python (3.14+)

## Getting Started

It is _highly_ recommended you create a virtual environment (venv) to install dependencies. A venv is effectively a dedicated sandbox for your project, so you can install and tear down dependencies without needing to install anything globally.

```bash
$ python -m venv .venv
```

Activate the environment, so VSCode will know how to use it.

For Mac/Linux:
```bash
$ source .venv/bin/activate
```
For Windows:
```bash
$ .venv\\Scripts\\activate
```

Now, install dependencies required for the training. First, we will install our dependency manager, `uv`.

```bash
$ pip install uv
```

Then, install dependencies from our lock file.

```bash
uv sync
```

## TODO

- Modernize the training plan to account for LLMs and other modern AI tooling.
- Subsections for MLOps.
- Update examples and questions to be more "government"/540 use-case specific.
- Re-organize lesson plans to be more "formulaic" - common formatting, and a lesson 0 explaining the format, and what folks should care about (ie. non-technical -> developer -> data scientist progression)
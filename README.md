# KMeans, AutoML, RAPIDS, and PyCaret

This repository contains my completed Colab work for the assignment on KMeans clustering and AutoML libraries. I copied the reference notebooks into my own Google Drive, ran them in Google Colab, fixed the issues needed for the current runtime, and saved the notebooks with their outputs included.

The videos linked below show my own Colab runs. In each video, I explain the important code, the main idea behind it, and what the output means. I focus on the machine-learning work and skip minor display or interface code.

## Contents

```text
.
├── README.md
├── 01_kmeans_clustering/
│   └── 01_kmeans_clustering_executed.ipynb
├── 02_autogluon_capabilities/
│   └── 02_autogluon_capabilities_executed.ipynb
├── 03_autogluon_end_to_end/
│   └── 03_autogluon_end_to_end_executed.ipynb
├── 04_rapids_cpu_gpu_comparison/
│   └── 04_rapids_cpu_gpu_comparison_executed.ipynb
├── 05_pycaret_capabilities/
│   └── 05_pycaret_capabilities_executed.ipynb
└── 06_pycaret_mlops/
    └── 06_pycaret_mlops_executed.ipynb
```

## Part 1: KMeans clustering and variations

This notebook demonstrates how KMeans groups similar data points into clusters. It covers the basic algorithm, choosing the number of clusters, visualizing the clusters, and relevant variations or evaluation methods included in the reference notebook.

- Google Colab copy: https://colab.research.google.com/drive/1j1g9J5198hLL9wIBLGybnPXP8WUwJ2vW#scrollTo=jdgSKbBsBTY1
- YouTube walkthrough: https://youtu.be/lT0EGSnYh8w

## Part 2: AutoGluon capabilities landscape

This notebook gives an overview of what AutoGluon can do for automated machine learning. It shows how the library can help with tasks such as tabular prediction and model selection while handling much of the training workflow automatically.

- Google Colab copy: https://colab.research.google.com/drive/1SE3_BWtwyEU_H-YrSYnmBtpBw40w3OKl?authuser=1#scrollTo=Inm6hfJgCqdT
- YouTube walkthrough: https://youtu.be/r_os3vYxMcE

## Part 3: AutoGluon end-to-end machine learning

This notebook follows a complete machine-learning workflow with AutoGluon. It includes preparing or loading data, training models, evaluating performance with metrics, comparing models, and using the trained predictor to make predictions.

- Google Colab copy: https://colab.research.google.com/drive/1AxVBwedMNl3msA1mur7m86ffZDfm7Mxl?authuser=1
- YouTube walkthrough: https://youtu.be/Rj98nt_CQnU

## Part 4: NVIDIA RAPIDS compared with CPU-based processing

This notebook compares CPU processing with GPU-accelerated processing using the NVIDIA RAPIDS ecosystem. The goal is to understand how GPU data-science libraries can speed up operations such as data loading, transformation, or machine-learning tasks when a compatible GPU is available.

- Google Colab copy: https://colab.research.google.com/drive/1WenVjeo00MZVxRssNY6ZhX4ebf3y-rUM?authuser=1
- YouTube walkthrough: https://youtu.be/knYs9qlSiBA

## Part 5: PyCaret capabilities landscape

This notebook explores PyCaret as a low-code AutoML library. It demonstrates how PyCaret can simplify common steps such as setting up an experiment, comparing models, selecting a model, evaluating it, and generating predictions.

- Google Colab copy: https://colab.research.google.com/drive/1A04mOC3iYHDvfemyJEdoTNiin4qBBqZk?authuser=1
- YouTube walkthrough: https://youtu.be/lnl82k3p4NI

## Part 6: PyCaret for MLOps

This notebook focuses on the MLOps side of PyCaret. It demonstrates the steps used to move from model experimentation toward a reusable machine-learning workflow, such as saving a trained pipeline or model and using it later for prediction or deployment-related work.

- Google Colab copy: https://colab.research.google.com/drive/1v4bVEovEzqJcr5MVOLIMf1NgoVl706Q3?authuser=1
- YouTube walkthrough: https://youtu.be/bFPoOBLXxck

## Main concepts I learned

- KMeans is an unsupervised learning method that groups observations by similarity.
- The number of clusters is an important choice and should be supported by analysis rather than chosen randomly.
- AutoGluon automates model training, comparison, and ensembling for several machine-learning tasks.
- RAPIDS uses GPU-based data-science libraries to accelerate compatible workloads.
- PyCaret provides a lower-code way to compare, tune, evaluate, save, and use machine-learning models.
- A successful notebook run is not enough by itself; reproducibility also requires the correct packages, data, runtime, and saved outputs.

## Reproducibility notes

The notebooks were executed in Google Colab. Package versions and hardware availability can affect runtime and results, especially for AutoGluon, PyCaret, and RAPIDS. The notebooks in this repository include the outputs from my runs so that the execution can be reviewed without relying only on the video.

Before rerunning a notebook, run its installation and setup instructions from top to bottom. For the RAPIDS notebook, select a Colab runtime with GPU support if the notebook requires it, and confirm that the GPU is actually detected before running the benchmark.

## Final submission checklist

- [ ] All six executed `.ipynb` files are uploaded.
- [ ] Outputs are visible in each notebook.
- [ ] Each notebook can be opened from the GitHub repository.
- [ ] Each notebook has a working Google Colab link.
- [ ] Each part has a separate YouTube walkthrough link.
- [ ] The videos show my own Colab execution and explanation.
- [ ] The repository is organized into clearly named folders.
- [ ] The GitHub repository URL is submitted to the course assignment.

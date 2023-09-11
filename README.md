[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KedoKudo/DT_GNN_Tutorial/blob/tree/main/notebooks/)

# A Graph Neural Network Tutorial for Spatiotemporal Learning on Digital Twin Networks

Welcome to the Graph Neural Network (GNN) tutorial using PyTorch, PyTorch Geometric, and PyTorch Geometric Temporal!
This tutorial is designed to introduce you to the world of graph neural networks and learn how to leverage existing library to quickly setup your own GNN models.
You can run these tutorials directly on Google Colab by clicking on the "Open in Colab" badge at the start of each notebook.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Tutorials](#tutorials)
- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)

## Overview

In this tutorial, you will:

- Understand the fundamentals of graphs and their significance in machine learning.
- Dive deep into the principles behind Graph Neural Networks.
- Explore PyTorch Geometric and leverage it to design GNNs.
- Venture into temporal graph networks with PyTorch Geometric Temporal.
- Work hands-on with various datasets and a simplified example in traffic prediction.

## Setup

To get started, ensure you have [Conda](https://docs.conda.io/en/latest/) installed for local setup.
For Google Colab users, most dependencies are pre-installed.
Additional dependencies for the tutorial can be installed directly within the notebook.

1. **Local Setup**:

   - Clone this repository and navigate to the root directory:

   ```bash
   git clone https://github.com/your_username/graph-gnn-tutorial.git
   cd graph-gnn-tutorial
   ```

   - Create the Conda environment from the `environment.yml` file:

   ```bash
   conda env create -f environment.yml
   ```

    > When using `micromamba` or `mambaforge`, double check the corresponding syntax from the official documentation. 

   - Activate the newly created environment:

   ```bash
   conda activate graph-gnn-tutorial-env
   ```

   - Launch Jupyter:

   ```bash
   jupyter lab
   ```

   > You can also use `jupyter notebook` if you prefer the classic interface.

   - [Optional] It is also a good idea to use `direnv` to automatically activate the environment when you enter the project directory.

2. **Google Colab Setup**:

   - Click on the "Open in Colab" badge at the beginning of each tutorial notebook.
   - Install required dependencies as guided in the notebooks.

Navigate to the `notebooks` directory to start the tutorials.

## Tutorials

Our tutorials are structured in a progressive manner.
You'll begin with foundational concepts and gradually delve into more complex topics and applications.
Although it is possible to read through the tutorials in any order, we recommend following the order below:

1. **Foundational Concepts**:
   - `01_intro_to_graphs.ipynb`: Introduce graph theory, its components, and significance.
   - `02_pytorch_basics.ipynb`: Understand PyTorch's tensors, autograd, and basic operations.
   - `03_gnn_intro.ipynb`: Explore the foundational principles behind Graph Neural Networks.

2. **PyTorch Geometric**:
   - `04_pytorch_geometric_intro.ipynb`: Dive into PyTorch Geometric, its utilities, and datasets.
   - `05_node_classification.ipynb`: Tackle node classification tasks using GNNs.
   - `06_graph_classification.ipynb`: Learn how to classify entire graphs with GNNs.

3. **Temporal Graph Networks**:
   - `07_pytorch_geometric_temporal_intro.ipynb`: Grasp the core concepts of temporal graphs and their dynamics.

4. **Case Studies**:
   - `08_traffic_prediction.ipynb`: A simple example of using GNN for traffic prediction.

## Datasets

This tutorial uses mostly synthetic and open dataset to showcase the capabilities of GNNs.
These datasets are located in the `data` directory.

- `sumo`: A synthetic network generated with [SUMO](https://www.eclipse.org/sumo/).

## Contributing

This is an open tutorial repository and we welcome contributions!
If you find an error, have a suggestion, or want to add more content, please open an issue or a pull request.
Make sure to follow the coding and content style present in the current tutorials.

## License

This tutorial is released under the [GPL-3.0 license](LICENSE).

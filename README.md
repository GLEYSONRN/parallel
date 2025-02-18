# Parallel Computing Project with Dask and Multi-GPU Training 

Welcome to the repository that explores **parallel computing techniques**, utilizing the **Dask** library for CPU processing and **multi-GPU implementation** for medical image analysis.

## 🌍 Overview

This repository contains two main notebooks:

1. **SUS Data Analysis with Dask**: Uses the Dask library to process and analyze large-scale healthcare data from the **Brazilian Unified Health System (SUS)** in São Paulo from 2008 to 2018. The focus is on demonstrating how Dask facilitates parallel processing on CPUs, enabling efficient handling of large datasets.

2. **Organelle Identification with BloodMNIST on Multiple GPUs**: Applies deep learning techniques to identify organelles in BloodMNIST images, leveraging multiple GPUs in parallel 🎮⚡. This notebook highlights how to distribute workload across multiple GPUs to speed up training and inference.

## 📚 Notebooks

### 1. SUS Data Analysis with Dask

- **Notebook**: [Final_SP.ipynb](https://github.com/GLEYSONRN/parallel/blob/main/Final_SP.ipynb)
- **Description**: This notebook demonstrates how to:
  - Load and manipulate large datasets that exceed RAM capacity.
  - Execute parallel data analysis operations using all available CPU cores.

### 2. Organelle Identification with BloodMNIST on Multiple GPUs

- **Notebook**: [Parallel_GPU.ipynb](https://github.com/GLEYSONRN/parallel/blob/main/Parallel_GPU.ipynb)
- **Description**: This notebook focuses on:
  - Implementing a deep learning model for **organelle classification** in BloodMNIST images.
  - Configuring the environment for **distributed training** using multiple GPUs, significantly reducing training time.
  - Monitoring and evaluating model performance during parallel training.

## 🛠️ Requirements

To reproduce the experiments, ensure you have installed:

- **Python 3.7 or higher**
- Required Python libraries:
  - `rapids` 
  - `dask` 
  - `pandas` 
  - `numpy` 
  - `matplotlib` 
  - `sklearn` 
  - `keras` 
  - `tensorflow` 
  
- **Hardware:**
  - For the Dask notebook: A **multi-core CPU**.
  - For the GPU notebook: **Multiple CUDA-compatible GPUs**.

## 🏗️ How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GLEYSONRN/parallel.git
   cd parallel
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebooks**:
   - Use **Jupyter Notebook** or **JupyterLab** to open and execute the `.ipynb` notebooks.

## 📖 References

- [📘 Dask Documentation](https://docs.dask.org/en/stable/)
- [⚡ Dask Parallel Computing Tutorial](https://computing.stat.berkeley.edu/tutorial-dask-future/python-dask.html)
- [🔥 Multi-GPU Training with Tensorflow](https://www.tensorflow.org/guide/keras/distributed_training)

Enjoy exploring parallel computing techniques! 🚀

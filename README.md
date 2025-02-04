# Image Compression Using PCA/K-Means

## Overview

This is my final project for CSCA 5632 at CU Boulder. I used PCA and K-Means clustering to reduce the size of images.

Citation:
```
Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, Technical Report, Computer Science Department, University of Toronto, 2009.

Available at: http://www.cs.toronto.edu/~kriz/cifar.html
```

## Structure

- `image-compression.ipynb`: A Jupyter notebook where I walk through my process to compress images using PCA/K-Means, tweak parameters, and compare results.
- `requirements.txt`: The required Python packages to run the notebook.

## How to Run

1. **Clone the repository**:

    ```bash
    git clone git@github.com:PrajnaAvidya/csca-5632-final.git
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv .venv
    source .venv/bin/activate
    ```

3. **Install packages**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the notebook**:

   Some IDEs like PyCharm run Jupyter notebooks automatically, but you can also use docker to spin up JupyterLab, or just install it locally. You can also review the contents/results of the notebooks on the GitHub website without having to run it locally.

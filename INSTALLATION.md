# Installation Instructions

## Prerequisites
- Ensure you have `conda` installed. You can install Miniconda or Anaconda from their official websites.
- Ensure you have Python installed. You can download it from the official Python website.

## Steps to Install RDKit Using Conda

1. Create a new conda environment (optional but recommended):
    ```sh
    conda create -n myenv python=3.8
    conda activate myenv
    ```

2. Install RDKit using conda:
    ```sh
    conda install -c conda-forge rdkit
    ```

3. Install other dependencies from `requirements.txt`:
    ```sh
    pip install -r requirements.txt
    ```

Now you should have RDKit and other dependencies installed in your environment.

## Steps to Install RDKit Using Venv

1. Create a new virtual environment:
    ```sh
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

2. Upgrade `pip`:
    ```sh
    pip install --upgrade pip
    ```

3. Install RDKit and other dependencies from `requirements.txt`:
    ```sh
    pip install -r requirements.txt
    ```

Now you should have RDKit and other dependencies installed in your virtual environment.

## Why Use Conda Over Venv?

1. **Package Management**: `conda` handles both package and environment management, making it easier to manage dependencies.
2. **Cross-Platform Compatibility**: Works consistently across Windows, macOS, and Linux.
3. **Precompiled Binaries**: Provides precompiled binaries for complex scientific libraries.
4. **Environment Isolation**: Can include non-Python dependencies in isolated environments.
5. **Channel Support**: Access to a wide range of packages through channels like `conda-forge`.
6. **Ease of Use**: Simplifies managing both Python and non-Python dependencies.

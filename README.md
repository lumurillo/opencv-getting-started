# opencv-getting-started
This repository provides beginner-friendly code samples and tutorials to help you get started with OpenCV, the popular open-source computer vision library.

## Setting Up a Python Environment with Miniforge

To create a Python environment using Miniforge, follow these steps:

1. **Download and Install Miniforge**  
    Visit [Miniforge GitHub Releases](https://github.com/conda-forge/miniforge#miniforge3) and download the installer for your operating system.  
    Run the installer and follow the prompts.

2. **Create a New Environment**  
    Open a terminal and run:
    ```bash
    conda create -n opencv-env python=3.10
    ```
    Replace `opencv-env` with your preferred environment name.

3. **Activate the Environment**  
    ```bash
    conda activate opencv-env
    ```

4. **Install depenencies**
    ```bash
    pip install -r requierements.txt
    ```

Your Python environment is now ready for OpenCV development!

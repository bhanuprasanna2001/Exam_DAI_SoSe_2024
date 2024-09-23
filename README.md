# Exam – DAI (SoSe 2024)
 
## Setup Guide

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo/project-name.git
cd project-name
```

### 2. Create and Activate the Environment

To ensure the project works smoothly across different operating systems, create a new environment using Conda:

```bash
conda create --name DAI_MR_RAA python=3.8
conda activate DAI_MR_RAA
```

### 3. Install Dependencies

#### Using `requirements.txt` (for pip-based installs):

```bash
pip install -r requirements.txt
```

#### Using `environment.yml` (for Conda-based installs):

```bash
conda env create -f environment.yml
conda activate DAI_MR_RAA
```

### 4. Run the Project

You can run the Python scripts or Jupyter notebooks as needed. For example:

- To run a Python script:

    ```bash
    python script_name.py
    ```

- To run a Jupyter notebook:

    ```bash
    jupyter notebook
    ```

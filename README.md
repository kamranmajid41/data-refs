# data-refs

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

This repository contains Jupyter/Colab notebooks with the code used in my research papers. The notebooks are organized to be easily understandable and reproducible, allowing readers to explore the analysis and results presented in my publications.

## Repository Structure

├── papers/
│   ├── paper_title_1/
│   │   ├── notebook_1.ipynb
│   │   ├── paper.pdf    
│   │   └── ... other related files
│   ├── paper_title_2/
│   │   ├── analysis.ipynb
│   │   └── data/
│   │       └── ...
│   └── ...
├── environment.yml     
├── requirements.txt   
├── CONTRIBUTING.md      
├── LICENSE            
└── README.md            


* **`papers/`**: This directory houses subdirectories, each corresponding to a specific research paper. The subdirectory name should ideally be related to the paper's title or a unique identifier.
* **`papers/paper_title_X/`**: Within each paper's directory, you'll find the Jupyter/Colab notebooks (`.ipynb` files) containing the code, along with any necessary data files or a specific `README.md` providing context for that paper's notebooks.
* **`environment.yml`**: A YAML file specifying the conda environment used to run the notebooks. This ensures reproducibility by listing all necessary Python packages and their versions.
* **`CONTRIBUTING.md`**: If you plan to accept contributions, this file outlines the guidelines for doing so.
* **`LICENSE`**: A text file containing the license under which your code is shared (e.g., MIT License, Apache License 2.0). Choose an open-source license to encourage reuse and collaboration.
* **`README.md`**: This top-level file provides an overview of the repository.

## Getting Started

To run these notebooks, you will need to have Python and Jupyter/Colab installed. We recommend using the provided environment file for consistency.

### Using `environment.yml`

1.  **Install Conda:** If you don't have Conda installed, follow the instructions on the [official Anaconda website](https://www.anaconda.com/products/distribution).
2.  **Create the environment:** Navigate to the root directory of this repository in your terminal and run:
    ```bash
    conda env create -f environment.yml
    ```
3.  **Activate the environment:**
    ```bash
    conda activate your_environment_name  # Replace 'your_environment_name' with the name specified in environment.yml
    ```
4.  **Install Jupyter:** If not already installed in the environment:
    ```bash
    conda install -c conda-forge jupyter
    ```
5.  **Open Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    or
    ```bash
    jupyter lab
    ```
    Navigate to the desired notebook within the repository structure.

### Running on Google Colab

Alternatively, you can directly open and run the notebooks on Google Colaboratory:

1.  Go to [https://colab.research.google.com/](https://colab.research.google.com/).
2.  Click "Upload" and select the desired `.ipynb` file from this repository.
3.  Colab provides a pre-configured environment with many common libraries. If a notebook requires specific packages not included, you can install them within the Colab notebook using `!pip install package_name`.

## Data

Where applicable, data files necessary to run the notebooks are included within the respective paper's directory (e.g., `papers/paper_title_2/data/`). If the data is too large or cannot be shared publicly, clear instructions on how to obtain or generate the data will be provided within the notebook or a specific `README.md` file in the paper's directory.

## Contributing 

If you are interested in contributing to this repository (e.g., fixing bugs, improving code clarity), please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## License

This code is released under the [MIT License](LICENSE). See the `LICENSE` file for more details.

## Citation

If you use the code in this repository for your research, please cite the corresponding paper(s). Citation information can usually be found in the paper itself.

## Contact

For any questions or issues regarding the code, please feel free to [open an issue](https://github.com/kamranmajid41/data-refs/issues) or contact me (kamranmajid41@gmail.com).

---
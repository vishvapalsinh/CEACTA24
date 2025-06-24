# CEA and CTA Analysis for BIODIV and BIOMEDICAL Datasets

This repository contains a Jupyter Notebook that demonstrates how to perform Comparative Effectiveness Analysis (CEA) and Comparative Taxonomic Analysis (CTA) on the BIODIV and BIOMEDICAL datasets. The notebook provides step-by-step instructions, including data preparation, analysis, and visualization.

## Contents

- `CEA_R2_BIODIV_TARGET.ipynb` : Jupyter Notebook with code and explanations for CEA BIODIV dataset .
- `CEA_R2_BIOMEDICAL_TARGET.ipynb` : Jupyter Notebook with code and explanations for CEA BIOMEDICAL dataset
- `CTA_R2_BIODIV_TARGET.ipynb.ipynb` : Jupyter Notebook with code and explanations for CTA BIODIV dataset
- `requirements.txt`: List of required Python packages.

## Installation

To use the Jupyter Notebook, you'll need to install the necessary Python packages. You can do this by creating a virtual environment and installing the packages listed in `requirements.txt`. Here are the steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/DKEPassau/CEACTA24.git

2. **Navigate to the project directory:**

   ```bash
   cd your-repository
   
3. **Create a virtual environment (recommended but optional):**

   ```bash
   python -m venv venv

4. **Activate the virtual environment Windows:**

   ```bash
   venv\Scripts\activate

5. **Activate the virtual environment MAC and Linux:**

   ```bash
   source venv/bin/activate
   
6. **Install the required packages:**

   ```bash
   pip install -r requirements.txt

7. **Launch the Jupyter notebook:**

   ```bash
   jupyter notebook
 

 ## Usage

1. **Open the Notebook:**
Start Jupyter Notebook and open `CEA_R2_BIODIV_TARGET.ipynb` and others.
2. **Follow the Instructions:**
The notebook contains step-by-step instructions and code for performing CEA and CTA. Follow the guide in the notebook to run the analysis.
3. **Datasets:**
Ensure that you have access to the BIODIV and BIOMEDICAL datasets. Update the file paths in the notebook to point to the locations of your datasets.

## Requirements

The notebook relies on the following Python packages:

- `pandas`
- `requests`
- `ratelimit`
- `concurrent.futures`
- `json`
- `re`
- `collections`
- `OrderedDict`

All required packages are listed in `requirements.txt`.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

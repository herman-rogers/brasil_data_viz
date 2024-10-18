## Brasil Data Visualization Project

This project provides data visualizations using Jupyter Notebooks for exploration, Pandas, and Matplotlib to generate insights.

---

## Setup and Installation

### Prerequisites
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (lightweight Conda installer)

### Step 1: Clone the Repository
```bash
git clone https://github.com/herman-rogers/brasil_data_viz.git
cd brasil_data_viz
```

### Step 2: Install the Conda Environment

Make sure you have Miniconda installed. Then, create the project environment using the environment.yml file:

```bash
conda env create -f environment.yml
```

### Step 3: Activate the Environment

After the environment is installed, activate it using:

```bash
conda activate brasil_data_viz
```

## Project Structure

```bash
├── data/
│   └── brasil.xlsx            # Cleaned data for analysis
├── notebooks/
│   ├── territories/*.ipynb  # Notebooks exploring favela territories
│   ├── policias_data.ipynb     # Notebook on police actions and impact
│   └── gac_data.ipynb         # Notebook on favelas
├── environment.yml          # Conda environment setup file
├── README.md                # Project documentation
```

## How to Use

1) Open Jupyter Notebooks: In your terminal, navigate to the project folder and run:

```bash
jupyter notebook
```

2) Explore the Notebooks: The notebooks are located in the notebooks/ folder:

    * territories/*.ipynb: Explore various territories and their data.
    * policias_data.ipynb: Data vis for police actions within the favelas.
    * gac_data.ipynb: Data vis for favelas.



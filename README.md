# Climarisc: Data-Driven Crop Vulnerability Curves

This project aims to derive and analyze crop vulnerability curves directly from observed, global-scale yield data to understand the impacts of climate extremes.

## Project Structure

- **/data**: Contains the raw data (`.nc4` files). This directory is not tracked by Git.
- **/notebooks**: Jupyter notebooks for exploratory data analysis (EDA) and experimentation.
- **/scripts**: Reusable Python scripts for data processing, analysis, and visualization.
- **/reports**: Generated figures, tables, and final project reports.
- `environment.yml`: The Conda environment specification file.

## Setup Instructions

To get started with this project, follow these steps:

1.  **Clone the repository:**
    `git clone <your-repo-url.git>`
    `cd climarisc`

2.  **Create the Conda environment:** This will install all necessary packages from the `environment.yml` file.
    `conda env create -f environment.yml`

3.  **Activate the environment:**
    `conda activate climarisc`

4.  **Add the data:** Download the Iizumi et al. dataset and place the `.nc4` files inside the `/data` folder.

5.  **Launch Jupyter Lab:**
    `jupyter lab`

    You can now open and run the notebooks in the `/notebooks` directory.
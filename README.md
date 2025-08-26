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

---

## Collaboration Workflow (Using VS Code)

To work together effectively and avoid conflicts, we will use the VS Code Source Control panel and follow this simple workflow.

### The Golden Rule: Sync Before You Work

Before you start writing any code, **always sync with the remote repository**. This pulls down any changes your partner has made and ensures you are working on the most up-to-date version of the project.

Think of it like refreshing a shared Google Doc before you start typing.

### The Daily Work Cycle

Here is the step-by-step process for making and sharing changes.

**1. Sync with GitHub (Get the latest changes)**

*   Open the **Source Control** panel in VS Code (the icon with three dots and branches).
*   Click the **"Sync Changes"** button at the bottom of the panel (it has a circular arrow icon).
*   This will "pull" any new commits from GitHub to your local machine.

**2. Do Your Work**

*   Now you can safely edit files, create new notebooks, or write scripts.

**3. Stage Your Changes (Choose what to save)**

*   Once you've completed a task, go back to the **Source Control** panel.
*   You will see your modified files under a "Changes" list.
*   Click the **`+` icon** next to each file you want to save in this snapshot. This moves them to "Staged Changes."

**4. Commit Your Changes (Save the snapshot)**

*   Above the "Staged Changes" list, there is a **message box**.
*   Write a short, clear message describing what you did (e.g., "Add initial plot for maize yield in the US").
*   Click the **checkmark icon** to "Commit." This saves the snapshot of your staged changes *locally* on your computer.

**5. Sync with GitHub (Share your work)**

*   Click the same **"Sync Changes"** button again.
*   This time, because you have new local commits, it will "push" your changes up to GitHub for your partner to see.

### Summary of the Workflow

-   **Start of your session:** Click **Sync Changes**.
-   **Finish a task:**
    1.  **Stage** your changes (`+` icon).
    2.  **Commit** them with a good message (checkmark icon).
    3.  Click **Sync Changes** to share.
-   **Communicate:** If you plan to work on the *exact same file* at the same time, give your partner a quick heads-up to avoid confusion.
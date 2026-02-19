# Comparative Implementation of Neural Networks, Evolutionary Algorithms, and Fuzzy Systems for Tabular Prediction

💡 **Note:**  
If you are new to Neural Networks (NN), Evolutionary Algorithms (EA), Fuzzy Systems (FS), or NRP JupyterHub, review the course materials before you start.

---

**Prerequisites**

Before you begin, ensure you have the following:

- **Git:** Install Git from its official website.
- **NRP.ai Account:** Access to the instructor-managed namespace.
- **NRP Stack:** PyTorch2 environment (required).
- **Linux/MacOS:** No extra setup needed.
- **Windows:** Use a modern browser to access NRP JupyterHub.

All final experiments must be executed on **NRP JupyterHub using the required PyTorch2 stack**.  
Docker is not used for this project.

---

**Step 1: Clone the Repository**

Clone the GitHub repository to your local machine:

```bash
git clone https://github.com/DrAlzahraniProjects/csusb_spring26_cse5140_team1.git
```

---

## Step 2: Navigate to the Repository

Change to the cloned repository directory:

```bash
cd csusb_spring26_cse5140_team1
```

---

## Step 3: Pull the Latest Version

Update the repository to the latest version:

```bash
git pull origin main
```

---

## Step 4: Launch **NRP JupyterHub**

1. Log in to **NRP.ai**.
2. Select the **instructor-provided namespace**.
3. Launch a Jupyter Notebook using the **NRP Stack PyTorch2 environment**.
4. Clone this repository inside your NRP workspace (or upload the repository files).

All reported results must be generated inside **NRP** to ensure **fairness and reproducibility**.

---

## Step 5: Run the Notebooks

In Jupyter, navigate to the **notebooks/** directory.

Run the notebooks in the following order:

1. **NN_Analysis.ipynb**  
2. **EA_Optimization.ipynb**  
3. **FS_Model.ipynb**  
4. **Final_Comparison.ipynb**  

Open each notebook.

Select **Run All Cells** to execute the code.

Each notebook must execute **end-to-end without manual intervention**.

---

## Step 6: Data Handling and Splitting

- The dataset is limited to the first **1,000,000 rows**.
- The data is shuffled using a **fixed random seed**.
- A strict **50% holdout set** is reserved and never accessed during model tuning.
- The remaining 50% is used for **development (training and validation)**.
- Final evaluation is performed once on the held-out **50% test set**.

---

## Step 7: Dataset Access

The dataset (~151 MB) is not stored directly in the repository.

To ensure **reproducibility** without exceeding GitHub size limits:

- The dataset is hosted as a **GitHub Release asset (v1.0)**.
- The notebook automatically downloads the dataset if it is not already present.
- The file is saved locally inside the **data/** directory using a relative path.
- No manual upload or **Kaggle API access** is required.

The contents of the **data/** directory are excluded via **.gitignore** to prevent large files from being committed to version control.

---

## Step 8: Environment Verification

Ensure that:

- All final results are generated on **NRP**.
- **Fixed random seeds** are used.
- **environment_summary.md** documents:
  - **NRP image used**
  - **Python version**
  - **Key library versions (pip freeze)**

💡 **Note:**  
All comparative experiments and reported metrics must originate from execution within the **NRP JupyterHub environment**.

---

## About

This repository contains the full **reproducible implementation** required for:

**CSE 5140 – Computational Intelligence**  
Spring 2026  

All notebooks execute end-to-end on **NRP JupyterHub using the PyTorch2 stack**.

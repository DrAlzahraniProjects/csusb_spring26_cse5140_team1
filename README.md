# Comparative Implementation of Neural Networks, Evolutionary Algorithms, and Fuzzy Systems for Tabular Prediction

💡 **Note:**  
If you are new to Neural Networks (NN), Evolutionary Algorithms (EA), Fuzzy Systems (FS), or NRP JupyterHub, review the course **Guide** before you start.

This project compares three different Artificial Intelligence methods to see how well they predict values from table-style data.


---

## Quick Start (For Graders)

1. Log into NRP.ai.
2. Launch PyTorch2 Jupyter environment.
3. Clone this repository.
4. Navigate to notebooks/.
5. Run notebooks in this exact order:

   1) NN_Analysis.ipynb
   2) EA_Optimization.ipynb
   3) FS_Model.ipynb
   4) Final_Comparison.ipynb

6. Each notebook runs end-to-end without modification.
7. All results are generated automatically.

No dataset upload is required.
No manual configuration is required.


---

**Prerequisites**

Before you begin, ensure you have the following:

- **[Git](https://git-scm.com/downloads)**: Install Git on your computer.
- **[NRP.ai Account](https://nrp.ai/)**: Access to the instructor-managed namespace.
- **[NRP Stack (PyTorch2 environment)](https://nrp.ai/)**: You must use the required PyTorch2 environment.
- **Linux/MacOS:** No extra setup needed.
- **[Windows](https://www.microsoft.com/en-us/software-download/windows11)**: Use a modern browser to access NRP JupyterHub.

All final experiments must be executed on **NRP JupyterHub using the required PyTorch2 stack**.  
Docker is not used for this project.

---

## Step 1: Launch **NRP JupyterHub** and Clone the Repository

1. Log in to **[NRP.ai](https://nrp.ai/)**.
2. Select the **instructor-provided namespace**.
3. Launch a Jupyter Notebook using the **NRP Stack PyTorch2 environment**.
4. Open a **Terminal** inside JupyterLab.
5. Clone the repository directly inside NRP:
```bash
git clone https://github.com/DrAlzahraniProjects/csusb_spring26_cse5140_team1.git
```
## Repository Structure

After cloning, your folder should look like this:

csusb_spring26_cse5140_team1/
│
├── notebooks/
│   ├── NN_Analysis.ipynb
│   ├── EA_Optimization.ipynb
│   ├── FS_Model.ipynb
│   └── Final_Comparison.ipynb
│
├── data/                (auto-created if missing)
├── environment_summary.md
├── README.md
└── requirements.txt (if applicable)

⚠️ Do not manually place files inside `data/`.
The dataset will download automatically when running NN_Analysis.ipynb.


6. Navigate into the repository directory:
```bash
cd csusb_spring26_cse5140_team1
```
7. Ensure the repository is up to date:
```bash
git pull origin main
```
Cloning inside **NRP JupyterHub** keeps the project organized and prevents file upload problems.

---

## Step 2: Dataset Access

The dataset (about 151 MB) is too large to store directly inside the repository.
To keep everything organized and reproducible:
- The dataset is stored as a **GitHub Release asset (v1.0)**.
- The notebook automatically downloads it if it is missing.
- The file is saved inside the **data/** folder.
- You do not need to manually upload anything.
- You do not need Kaggle API access.

The **data/** folder is excluded using **.gitignore** so large files are not uploaded to GitHub by mistake.

---

## Step 3: Run the Notebooks

In Jupyter, navigate to the **notebooks/** folder.
Run the notebooks in the following order:

1. **NN_Analysis.ipynb**  
2. **EA_Optimization.ipynb**  
3. **FS_Model.ipynb**  
4. **Final_Comparison.ipynb**  

For each notebook:

- Open it
- Click **Run All Cells**

Each notebook must run from start to finish without stopping or requiring manual changes.

---

## Step 4: Data Handling and Splitting

To ensure fairness and reproducibility:

- The dataset is limited to the first 1,000,000 rows.
- The data is shuffled using a fixed random seed.
- The dataset is split into:
  - 70% Training
  - 15% Validation
  - 15% Testing
- The test set is accessed only once for final evaluation.
- Validation data is used strictly for tuning.
---

## Step 5: Environment Verification

Make sure that:

- All final results are generated on NRP.
- Fixed random seeds are used.
- The file **environment_summary.md** includes:
  - The NRP image used
  - The Python version
  - The main library versions (using pip freeze)


 ## Expected Runtime (NRP Environment)

All experiments must be run on the NRP PyTorch2 stack.

Approximate runtime (may vary slightly):

- NN_Analysis.ipynb: ~10–20 minutes
- EA_Optimization.ipynb: ~20–40 minutes (depends on compute budget)
- FS_Model.ipynb: ~5–10 minutes
- Final_Comparison.ipynb: ~5 minutes

Total runtime for full project execution: ~45–75 minutes.

No manual tuning or interaction is required during execution.
Simply click "Run All Cells" for each notebook.
---

## Compute Budget Transparency

The EA optimization uses:

- Fixed population size
- Fixed number of generations
- Fixed evaluation procedure

The total number of model evaluations is printed in the notebook output.
Wall-clock time is recorded and displayed.
All experiments are executed on the same NRP hardware configuration.

---


💡 **Important**:
All reported results must come from running the project inside **NRP JupyterHub**.

---

## About

This repository contains the complete and reproducible implementation for:

CSE 5140 – **Computational Intelligence**
Spring 2026

All notebooks are designed to run fully on **NRP JupyterHub** using the **PyTorch2** stack.


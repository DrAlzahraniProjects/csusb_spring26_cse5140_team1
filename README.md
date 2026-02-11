# Enhancing Computational Intelligence Models Using Neural Networks, Evolutionary Algorithms, and Fuzzy Systems

💡 **Note:**  
If you are new to Neural Networks (NN), Evolutionary Algorithms (EA), Fuzzy Systems (FS), or NRP JupyterHub, review the course materials before you start.

---

## Prerequisites

Before you begin, ensure you have the following:

- **Git:** Install Git from its official website.
- **NRP.ai Account:** Access to the instructor-managed namespace.
- **NRP Stack:** PyTorch2 Environment (required).
- **Linux/MacOS:** No extra setup needed.
- **Windows:** Use a modern browser to access NRP JupyterHub.

All final experiments must be executed on **NRP.ai using the NRP Stack PyTorch2 environment**.

---

## Step 1: Clone the Repository

Clone the GitHub repository to your local machine:

git clone https://github.com/YOUR_USERNAME/csusb_spring26_cse5140_team1.git


---

## Step 2: Navigate to the Repository

Change to the cloned repository directory:

cd csusb_spring26_cse5140_team1


---

## Step 3: Pull the Latest Version

Update the repository to the latest version:

git pull origin main


---

## Step 4: Launch NRP JupyterHub

1. Log in to **NRP.ai**.
2. Select the instructor-provided namespace.
3. Launch a Jupyter Notebook using the **NRP Stack PyTorch2 environment**.
4. Clone this repository inside your NRP workspace (or upload the files).

All reported results must be generated inside NRP.

---

## Step 5: Run the Notebooks (In Order)

Open and execute the notebooks sequentially:

1. `NN_Analysis.ipynb`  
2. `EA_Optimization.ipynb`  
3. `FS_Model.ipynb`  
4. `Final_Comparison.ipynb`  

Each notebook must execute **end-to-end without manual intervention**.

---

## Step 6: Verify Reproducibility

Ensure the following:

- The dataset used is **NYC Taxi Trip Duration (Team 1 dataset)**.
- Only the first **1,000,000 rows** are used.
- Data split follows the required **70/15/15 train/validation/test ratio**.
- Fixed random seeds are applied.
- Final evaluation metrics are generated on **NRP**.
- `environment_summary.md` documents:
  - NRP image used
  - Python version
  - Key library versions (`pip freeze`)

---

💡 **Note:**  
Final experiments, comparative runs, and all reported results must be executed on NRP.ai to ensure fairness and reproducibility.

---

## About

This repository contains the complete semester-long implementation for **Team 1** in:

**CSE 5140 – Computational Intelligence (Spring 2026)**  
California State University, San Bernardino  

### Dataset  
NYC Taxi Trip Duration  
Target Variable: `trip_duration` (seconds)

---

## Phase 1: Neural Networks (NN)

**Research Questions**

- RQ1: How well can a neural network predict trip_duration?
- RQ2: Which features contribute most to predictive performance?

**Completion Includes**

- Linear Regression baseline
- PyTorch Neural Network implementation
- Regularization (dropout, weight decay)
- Hyperparameter tuning
- Feature importance (SHAP or permutation importance)
- Metrics: RMSE, MAE, R²

---

## Phase 2: Evolutionary Algorithms (EA)

**Research Question**

- RQ3: Can evolutionary algorithms improve NN performance?

**Completion Includes**

- Genetic Algorithm for hyperparameter and/or feature optimization
- Fitness convergence visualization
- Performance comparison against Phase 1 NN
- Execution under fixed computational budget

---

## Phase 3: Fuzzy Systems (FS)

**Research Question**

- RQ4: Can fuzzy systems provide competitive performance while improving interpretability?

**Completion Includes**

- Fuzzy inference system implementation
- Rule base documentation
- Predictive performance comparison
- Interpretability analysis

---

## Final Phase: Integrated Comparison

**Research Questions**

- RQ5: What are the trade-offs between accuracy, optimization cost, and interpretability?
- RQ6: Which CI method is most suitable for this dataset and why?

**Completion Includes**

- Side-by-side comparison table
- Normalized metrics (R², MAPE)
- Statistical validation (paired tests or confidence intervals)
- Evidence-based final conclusion

---

## Repository Files

- `NN_Analysis.ipynb`
- `EA_Optimization.ipynb`
- `FS_Model.ipynb`
- `Final_Comparison.ipynb`
- `environment_summary.md`
- `README.md`

All notebooks execute end-to-end on **NRP JupyterHub using the PyTorch2 stack**.

---

## Team

**Project Manager**  
David Forero  

**AI Engineers**  
Nadir Esmail – NN Specialist  
Brandon Kirk – EA Specialist  

**Data Engineers**  
Dominic Arrezola – Evaluation Specialist  

**Support Engineers**  
Iran Bojorquez – Research Assistant & Documentation Lead  
Jean Bustamante – Visualization & QA Tester  

---

## License

For academic use only.

# CSE 5140 – Computational Intelligence Project

Spring 2026

## 💡 Note:

If you are new to Computational Intelligence, Machine Learning models, or our selected methodology, please review the course materials before starting.

---

## Prerequisites

Before you begin, ensure you have the following:

* Git: Install Git from its official website.
* Docker: Install Docker from its official website.
* API Keys (if applicable to your project)
* Linux/MacOS: No extra setup needed.
* Windows: Install WSL and enable Docker's WSL integration.

---

## Step 1: Clone the Repository

Clone the GitHub repository to your local machine:

```
git clone https://github.com/YOUR_USERNAME/csusb_spring26_cse5140_team1.git
```

---

## Step 2: Navigate to the Repository

```
cd csusb_spring26_cse5140_team1
```

---

## Step 3: Pull the Latest Version

```
git pull origin main
```

---

## Step 4: Modify Script Permissions

```
chmod u+x docker_image_setup.sh
```

---

## Step 5: Build and Run the Docker Container

⚠️ Warning: Ensure port 8888 is free before running the container.

Run:

```
./docker_image_setup.sh
```

---

## Step 6: Access the Jupyter Notebook

Once the container starts, the terminal will display a URL (e.g., http://127.0.0.1) with a token.

Copy and paste this URL into your browser to access the Jupyter Notebook interface.

---

## Step 7: Run the Notebook

In Jupyter:

* Open `Long_lab.ipynb` (core implementation)
* Or open `Short_lab.ipynb` (condensed version)

Select **Run All Cells** to execute.

---

## Project Overview

This repository contains all source code, experiments, documentation, and evaluation results for the CSE 5140 semester-long team project.

---

## Repository Structure

* `Long_lab.ipynb` – Full implementation notebook
* `Short_lab.ipynb` – Streamlined notebook
* `Dockerfile` – Container configuration
* `docker_image_setup.sh` – Docker setup script
* `/docs` – Documentation
* `/data` – Datasets
* `/results` – Experimental outputs

---

## Team Members

| No. | Name             | Role                                    |
| --- | ---------------- | --------------------------------------- |
| 1   | Dominic Arrezola | Evaluation Specialist                   |
| 2   | Iran Bojorquez   | Research Assistant & Documentation Lead |
| 3   | Jean Bustamante  | Visualization & QA Specialist           |
| 4   | Nadir Esmail     | Neural Network Specialist               |
| 5   | Brandon Kirk     | EA Specialist                           |
| 6   | David Forero     | Project Manager                         |

---

## Course

CSE 5140 – Computational Intelligence
California State University, San Bernardino

---

## License

For academic use only.

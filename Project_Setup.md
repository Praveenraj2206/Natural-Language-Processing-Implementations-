# Project Setup (Anaconda Prompt – Conda Environment)

This project is designed for systems where **administrator permission is not available**.
We use **Anaconda Prompt** and a **Conda environment** to install all required packages locally
and run the project using **Jupyter Notebook**.

⚠️ This project uses **Conda environments**, not Python `venv`.
Do not mix `venv` and `conda`.

---

## Step 1: Open Anaconda Prompt

1. Press the **Windows key**
2. Search for **Anaconda Prompt**
3. Open it

---

## Step 2: Create a Conda Environment

```bash
conda create --name myenv
```
When prompted, type "y" and press Enter.

---

## Step 3: Activate the Conda Environment

```bash
conda activate myenv
```

---

## Step 4: Install Required Packages

```bash
pip install -r requirements.txt    
```
ex: replace "requirements.txt" with particular implementation's requirements file as "requirements_word_suggestion.txt"

---

## Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Step 6: Run the Required Implementation

1. Open the required notebook
2. Select Kernel → Python (myenv)
3. Run the required cells
   
---

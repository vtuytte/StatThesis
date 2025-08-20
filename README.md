# Thesis Code Repository

This repository contains the code and data used for my thesis: *N-grams as characteristic features of speakers*. The main components are an **RMarkdown project** for the analyses and plots, and a **Python notebook** for training autoencoders.  

## Main Files
- **`thesis.Rmd`** – RMarkdown file containing all analyses and plots presented in the thesis (excluding autoencoder training).  
- **`Thesis.Rproj`** – R project file to manage the RMarkdown workflow.  
- **`Training_autoencoder.ipynb`** – Jupyter notebook used to train the autoencoders and generate the autoencoder encodings.  
- **Encodings (already generated):**  
  - `encodings_AE_simple.csv`  
  - `encodings_AE_advanced.csv`  
  - `encodings_MFA_simple.csv`  
  - `encodings_MFA_advanced.csv`  

> ⚠️ **Note:** Running `Training_autoencoder.ipynb` is not necessary, since all precomputed encodings used in the thesis are already included.  
> You can run `thesis.Rmd` independently of the Python notebook.  

## Data
- **`data_Ngr.csv`** – Original dataset used in the thesis.  
- **`data_Ngr_cleaned.csv`** – A modified version of the dataset used for the Python notebook (diacritic characters were removed to ensure compatibility with Python).  
- **`freq_table.csv`** – Frequency table of all speeches, indicating how many times each n-gram appears within each speech.  

# Workshop in single-cell RNA-Sequencing Analysis

Welcome to the workshop that walks you through the standard analysis perfomed on single-cell RNA-Sequencing (scRNA-Seq) data.

## Workshop Structure

The workshop is designed around 3 sessions, each of which lasts for ~50 minutes. The structure is the following.

1. **Introduction** 
    - Theory: Short introduction to single-cell transcriptomics (~5 mins).
2. **Session A** 
    - Theory: Pre-processing & HVGs detection (~15 mins).
    - Hands-on: Pre-processing & HVGs detection (~35 mins).
3. **Session B**
    - Theory: Dimensionality reduction & clustering (~15 mins).
    - Hands-on: Dimensionality reduction & clustering (~35 mins).
4. **Session C**
    - Theory: Cell type annotation (~15 mins).
    - Hands-on: Cell type annotation (~35 mins).
5. **Q & A** 
    - Theory: Closing remarks (~10 mins).

## File Sructure

```
session_a/
├── session_a.ipynb         # Jupyter notebook with code for pre-processing and HVGs detection
├── pbmc.csv.gz             # Raw counts expression matrix
├── annotation.csv.gz       # Table with annotation information
session_b/
├── session_b.ipynb         # Jupyter notebook with code for dimensionality reduction and clustering
session_c/
├── session_c.ipynb         # Jupyter notebook with code for cell type annotation
├── sctype.csv              # Table with marker gene lists
slides/
├── scRNA-seq_analysis.pdf  # Workshop slides
env.yml                     # Conda environment
requirements.txt            # List of dependencies
```

## Dependencies Installation

All dependencies are listed within `requirements.txt`.

### Installing dependencies with pip

In case you are working on an environment that already has Python installed, open a terminal and execute the following command.

`pip install -r requirements.txt`

### Working with conda

In case you are using conda to manage environments, open a terminal and execute the following command.

`conda create --file conda_env.yml`

## Contact

### Authors

- Haris Manousaki (0009-0001-1356-2710), Information Management Systems Institute, Athena Research Center, Hellenic Republic

- Charis Sinnis (0000-0001-6231-0299), Information Management Systems Institute, Athena Research Center, Hellenic Republic

- George Georgakilas (0000-0003-1160-5753), Information Management Systems Institute, Athena Research Center, Hellenic Republic
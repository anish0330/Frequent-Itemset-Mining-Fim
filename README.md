# Market Basket analysis Using Frequent Itemset Mining (FIM).
This repository contains a market basket analysis of a online jerewellery business using the [Frequent Itemset Mining](https://www.geeksforgeeks.org/frequent-item-set-in-data-set-association-rule-mining/) (FIM). Frequent itemset mining is a fundamental technique in data mining, essential for discovering associations, patterns, and relationships within large datasets. It is widely used in various applications such as market basket analysis, recommendation systems, and fraud detection. The goal of frequent itemset mining is to identify sets of items that frequently occur together in a dataset, which can provide valuable insights into the underlying data.

## Data Disclaimer

This project utilizes proprietary data, which cannot be shared publicly due to confidentiality agreements. As a result, the datasets used in this analysis are not included in this repository.

### How to Use This Repository

1. **Project Overview**: The code and methodology used in this project are fully documented and can be reviewed in the provided notebooks and scripts.
2. **Reproducing the Analysis**:
    - If you have access to similar data or a suitable dataset, you can modify the data loading sections of the code to use your data.
    - Ensure that your data follows a similar format and preprocessing steps as described in the data structure section.
3. **Contact Information**: For any questions or further information regarding the data or project, please contact anishpati3003@gmail.com

### Note
While the specific dataset cannot be shared, all code, methodologies, and documentation are provided to facilitate understanding and replication of the analysis using your own data.

The features used to create the transactional database were `Name` and `Lineitem name`. These features correspond to the id of purchase and name of the item bought. It has been segregated based on year- month of purchase. If you have similar features, the codes in the notebook can be directly applied by changing dataset and feature names.



## Prerequisites
Before you begin, ensure you have met the following requirements:

You have installed the latest version of [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
## Installation
To install this project, follow these steps:
```bash
conda env create -f environment.yml -n custom_env_name
```
This command will create a new Conda environment that includes the dependencies needed for the project.
## Usage
To use this project, follow these steps:
```bash
conda activate <env_name>
jupyter notebook
```
Replace <env_name> with the name of the Conda environment specified above. This will activate the environment and start Jupyter Notebook, where you can open and run the notebook file.
## Contributors
 * Anish Pati

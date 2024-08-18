# Optimizing Urban Mobility Using LSTM and GRU Models

## Overview
This project focuses on predicting urban traffic volumes using advanced neural network models, specifically Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks. 
The dataset used includes traffic volume data along with temporal and weather-related features. The goal is to develop predictive models that assist in effective urban traffic management.

## Project Structure

- **src**: Contains all the source code and Jupyter notebooks.
  - **model**: Implementation of the LSTM and GRU models.
  - **main.ipynb**: The main Jupyter Notebook that ties together the entire workflow.
  - **experiments**: Contains various experimental notebooks for testing different configurations and approaches.
  - **eda.ipynb**: Jupyter Notebook for Exploratory Data Analysis (EDA).
  
- **dataset**: Contains the dataset used for training and evaluating the models.
  - **Metro_Interstate_Traffic_Volume.csv**: The primary dataset for the project.
  - **images**: Folder for storing images generated during the project.
  
- **DOCUMENTS**: Contains related documentation and presentations.
  - **PPT**: PowerPoint presentations.
  - **PDF**: Final report and other documentation in PDF format.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch (for implementing LSTM and GRU models)
- Pandas, NumPy, Matplotlib, Seaborn (for data analysis and visualization)

### Installation
1. Clone the repository:

   git clone [https://github.com/NAS-510/Optimizing-Urban-Mobility]
 
## Usage
1. **Run Jupyter Notebooks:**
   - Open the Jupyter notebooks in the `/src` directory to follow along with the data preprocessing, model training, and evaluation steps:
     ```bash
     jupyter notebook src/main.ipynb
     jupyter notebook src/eda.ipynb
     ```

2. **View Results:**
   - The results of the model evaluations, including performance metrics and visualizations, can be found within the respective notebooks or in the `dataset/images` directory.

## Dataset
The dataset used in this project is the **Metro Interstate Traffic Volume** dataset, which is stored in the `/dataset` directory. 
For more details about the dataset, refer to the relevant notebook or [Appendix C in the `DOCUMENTS/PDF/REPORT.pdf`].
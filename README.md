#hERG Blocking prediction with MLPClassifier 

Introduction

This project aims to predict toxicity using machine learning models. The dataset used for this project is sourced from the TDC Commons, specifically the HERG-Karim et al. dataset. The repository contains a Jupyter Notebook (.ipynb file) that includes the code for data processing, model training, and evaluation.

Where is the Data
The dataset can be found at the following link: TDC Commons - HERG-Karim et al.

How to Download the Repository
To download the repository, you can use the following command:

git clone <repository_url>
Replace <repository_url> with the actual URL of your repository.

Setting Up the Virtual Environment
To ensure that all dependencies are correctly installed and managed, it is recommended to use a Conda virtual environment. Follow these steps to set up the environment and install the required packages:

Create a Conda Environment
Open your terminal or command prompt and run the following command to create a new Conda environment. You can name the environment toxicity_env or any other name you prefer.

conda create --name toxicity_env python=3.8
Activate the Conda Environment
Activate the newly created environment using the following command:

conda activate toxicity_env
Install Packages
Open the Jupyter Notebook in Visual Studio Code (VSCode). Ensure that the kernel is set to the Conda environment you just created. You can select the kernel by clicking on the kernel name in the top right corner of the notebook interface and choosing toxicity_env.

In the first code cell of your notebook, include the following line to install the necessary packages:

!pip install pytdc xgboost rdkit scikit-learn pandas numpy
Run the Notebook
After installing the packages, you can run the cells in the notebook to execute the code.

###Conclusion
By following these steps, you will be able to set up the environment and run the code in the Jupyter Notebook to perform toxicity prediction using the provided dataset. If you encounter any issues or have any questions, feel free to reach out for assistance.

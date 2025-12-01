This is a series of notebooks which follow the workflow of Group V's CSC1171 Project

This project was conducted in jupyter notebooks run on the anaconda prompt commandline in a conda environment

This project was conducted on a laptop using a Ryzen AI 7 350 processor / GPU / NPU, 16 GB of 5600 mts RAM and a 500 GB M.2 NVME SSD.

All the results in the paper can be achieved by running the "25.11.29 Pivot.ipynb" notebook cell-wise. The rest of the notebooks contain various attempts, processes we followed, and different approaches to the problem.

The "25.09.27 Molecular Space.ipynb" notebook can be used to generate the data used in our class presentation during week 5-6.

This .zip file contains a series of notebooks, datasets as ".csv" files that were used during the project, and saved models we generated as ".pkl" files. Note, ".pkl" files are version dependent, and will not produce usable results unless the code is run with the specified versions of each package listed below (under Dependencies)

These notebooks rely on the ".csv" formatted datasets in order to run, and they must be placed in the same filepath / folder as the notebook when running.

Individual molecules can be screened for potential kinase inhibition using the "25.11.29 Importing pickles.ipynb" notebook

Dependencies:
catboost 1.2.8
joblib 1.5.1
lightgbm 4.6.0
matplotlib 3.10.3
numpy 2.2.6
pandas 2.3.0
rdkit 2025.3.3
scikit-learn 1.7.2
scikit-posthocs 0.11.4
seaborn 0.13.2
xgboost 2.0.3

All dependencies can be installed using the "25.12.01 Pips.ipynb" notebook, or by running:
!pip install {packagename}=={packageversion}
e.g., for installing numpy 2.2.6:
!pip install numpy==2.2.6
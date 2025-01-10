# First navigate to your project directory (using either method above)
cd "~/Desktop/TU PHD/Project Apple-leaves-pathology/Apple Pathology Notebooks/ResNet"

# Then activate the virtual environment
cd resnet_gpu_env_02
source bin/activate

# Navigate back to your working directory
cd ..

# Start Jupyter notebook
jupyter notebook


## Converting Jupyter Notebook to Python

To convert the Jupyter notebook to a Python script, follow these steps:

1. Open your terminal and navigate to the project directory:
   ```bash
   cd "/home/peter/Desktop/TU PHD/Project Apple-leaves-pathology/Apple Pathology Notebooks/ResNet"

   Use the jupyter nbconvert command to convert your notebook:
 ```bash
bashCopyjupyter nbconvert --to python YOUR_NOTEBOOK.ipynb

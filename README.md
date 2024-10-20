# Guest lecture: CLIMATE405 at the University of Michigan 

Course materials for the guest lecture "Machine Learning Application in Hydrology" of CLIMATE405 at the University of Michigan.

## Repo Structure
```
.
+-- MLApplicationinHydrology.pdf
+-- rainfall_runoff_modeling.ipynb
+-- rain_runoff.csv
+-- environment.yml
+-- model.pth
+-- README.md
```
- `MLApplicationinHydrology.pdf`: course slides.
- `rainfall_runoff_modeling.ipynb`: the jupyter notebook for an example of appling LSTM in rainfall-runoff modeling.
- `rain_runoff.csv`: the runoff and atmospheric forcings used by `rainfall_runoff_modeling.ipynb`.
- `model.pth`: a pretrained LSTM model in `rainfall_runoff_modeling.ipynb`.
- `environment.yml`: the YAML file for creating the conda virtual environment used by `rainfall_runoff_modeling.ipynb`.
- `README.md`: the readme file.


## Execute the jupyter notebook
### Step 1 -- Download conda and install the dependencies
To get started download [miniconda](https://docs.conda.io/en/latest/miniconda.html), and then use the `conda` command to create an python virtual environment:

    conda env create -f environment.yml

You can find the `environment.yml` file in this repository.

### Step 2 -- Open the notebooks through Jupyter Lab
Now launch an instance of jupyterlab from the command line:

    jupyter lab

A browser window will start up, and you can navigate to the notebook `rainfall_runoff_modeling.ipynb`.

### Step 3 -- Run notebook
Run the notebook cell by cell.


## Contacts
Peishi Jiang (peishi.jiang@pnnl.gov)

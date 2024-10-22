# Guest lecture: CLIMATE405 at the University of Michigan 

Course materials for the guest lecture "Machine Learning Applications in Hydrology" of [CLIMATE405 at the University of Michigan](https://github.com/mombadi/umich-climate405).

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


## Executing the Jupyter Notebook
The notebook [rainfall_runoff_modeling.ipynb](./rainfall_runoff_modeling.ipynb) contains an example of developing a rainfall-runoff model using LSTM. Please follow the instructions below to execute the notebook.

- **Step 1:** get started download [miniconda](https://docs.conda.io/en/latest/miniconda.html), and then use the `conda` command to create an python virtual environment:
```sh
    conda env create -f environment.yml
```

- **Step 2:** Now launch an instance of jupyterlab from the conda virtual environment:
```sh
    conda activate ml
    jupyter lab
```
A browser window will start up, and you can navigate to the notebook `rainfall_runoff_modeling.ipynb`.

- **Step 3:** Run the notebook `rainfall_runoff_modeling.ipynb` cell by cell.


## Contacts
Peishi Jiang (peishi.jiang@pnnl.gov)

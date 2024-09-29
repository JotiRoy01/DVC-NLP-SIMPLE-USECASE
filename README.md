# dvc-project-template
DVC project template

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.10 -y
```
```bash
source activate
```
```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```
## Reference repository
[reference repo](https://github.com/JotiRoy01/DVC-TEMPLATE.git)

## Move data from previous directory to currunt directory and create ./data folder simultenously
```bash
mv ../NLP_data/ ./data
```
## Create stage_01
```bash
cp src/stage_00_template.py src/stage_01_prepare.py
```
### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository
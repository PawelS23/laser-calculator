# Laser and optics calculator

## Local development setup

The instructions below presume you have cloned this git repository you are in a command line
(¨`bash`, `cmd` etc.) in the root directory of this project.

### conda environment

For the first time, create a new `laser-calculator` conda environment with necessary packages using
```
conda env create -f environment.yaml
```

This environment must be updated when the `environment.yaml` file changes using
```
conda env update -f environment.yaml
```

Every time you are working on the project, activate the environment using
```
conda activate laser-calculator
```

This is especially useful for local development.

### Adding new functions

New function can be added to the `functions.json` file. The definition should follow the same structure as is already present. The displayed equations are generated by webpage https://latex.codecogs.com/legacy/eqneditor/editor.php, downloaded in png format with the same name as is the name of the function definition and saved in the `formulas` folder.
# Bayesian Modeling with PyMC

This repository contains a Jupyter Notebook demonstrating a Bayesian model using PyMC with simulated decay data.

## 1. Install Pixi

Pixi is used to manage the project environment and dependencies.

- **[Pixi.sh installation instrucions](https://pixi.sh/latest/advanced/installation/)

## 2. Set Up the Environment

With Pixi installed, set up the project environment cding to the project directory and running:

```bash
pixi install
```

This command will create a virtual environment and install all required dependencies, including Jupyter, PyMC, ArviZ, and related tools, as specified in the `pixi.toml` file. You do not need to install these packages manually.

## 3. Open the Notebook

After the environment is set up, you can open the notebook using one of the following methods:

### Option A: Jupyter Lab

If you prefer using Jupyter Lab:

```bash
pixi run jupyter lab
```

Then, open the `mutant_model.ipynb` file from the file browser.

### Option B: Jupyter Notebook

If you prefer using the classic notebook interface:

```bash
pixi run jupyter notebook
```

Navigate to `mutant_model.ipynb` in your browser.

### Option C: Visual Studio Code (VSCode)

1. **Install VSCode:**  
   Download and install VSCode from [here](https://code.visualstudio.com/).

2. **Install the Python Extension:**  
   In VSCode, open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`) and install the "Python" extension.

3. **Open the Project Folder:**  
   Open the folder containing your project in VSCode.

4. **Open the Notebook:**  
   Locate and open `mutant_model.ipynb`. When prompted, select the Pixi environment as the Python interpreter. You can ensure it's active by running:

   ```bash
   pixi run code .
   ```

   This opens VSCode with the correct environment active.

## 4. Running the Notebook

Once the notebook is open, run the cells sequentially to perform the full Bayesian analysis. The notebook includes steps for:

- Simulating data
- Visualizing group differences
- Defining and fitting a Bayesian model
- Running prior and posterior predictive checks
- Diagnosing the model

Enjoy exploring Bayesian modeling with PyMC!

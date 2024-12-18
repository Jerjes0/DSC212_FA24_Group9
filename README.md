# DSC212_FA24_Group9
# Project Name
Euler's and Runge-Kutta Method for solving the SIER Model equations

## Members
- A69031744: [Zida Jin]()
- A09747831: [Conan Minihan](https://github.com/ConanMinihan)
- A69031567: [Tamar Schaap]()
- A69031541: [Jerjes Aguirre](https://github.com/Jerjes0)

## Description
This project aims to compare the performance of Euler's and RK4 methods for solving the set of equations given by the SEIR model on the context of the COVID19 pandemic.

## Installation Instructions
To install and run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/DSC212_FA24_Group9/DSC212_FA24_Group9.git`
2. Navigate to the project directory: `cd DSC212_FA24_Group9`
3. Create a virtual environment: `python -m venv numerical_env`
4. Activate the virtual environment: `source numerical_env/bin/activate` (on Linux/Mac) or `myenv\Scripts\activate` (on Windows)
5. Install dependencies: `pip install -r requirements.txt`
6. Add the virtual environment as a kernel in your Jupyter notebook or IDE using ipykernel: `python -m ipykernel install --user --name=numerical_env --display-name "numerical_env"`
7. Select the kernel in the right upper corner; Select Another Kernel, Python Environments... numerical_env
8. Run the notebook: `notebooks/euler_rk4_method.ipynb`

## Requirements
- Python 3.8 or higher
- pip package manager
- numpy
- scipy
- pandas
- matplotlib
- sklearn

## Expected results

### Euler's Method Result
![Euler's Method Result](figs/fig1.png)

### RK45's Method Result
![RK45's Method Result](figs/fig2.png)

### Stability test
![Stability test](figs/fig3.png)

### Stiffness test
![Stiffness test](figs/fig4.png)

### Long simulation test
![Long simulation test](figs/fig5.png)

### California data fit
![California data fit](figs/fig7.png)

### US (WHO) data fit
![ US (WHO) data fit](figs/fig8.png)

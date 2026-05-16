## Project Description

This project is a Python-based computational fluid dynamics (CFD) analysis framework designed to investigate turbulence transition and pressure loss in two-dimensional channel flow using Navier–Stokes simulation data.

The system applies data preprocessing, statistical analysis, correlation analysis, and visualization techniques to study the behavior of fluid flow variables such as velocity, pressure, and velocity gradients. The framework uses an object-oriented programming (OOP) approach to organize the computational pipeline into modular and reusable components.

The dataset undergoes several preprocessing stages including duplicate removal, missing value imputation, and index-based filtering to improve computational efficiency while preserving the physical characteristics of the simulated flow system.

The project generates multiple visualizations including:
- Histograms
- Scatter plots
- Boxplots
- Correlation heatmaps
- Pressure evolution animations
- Velocity field visualizations

Statistical methods such as mean, median, variance, standard deviation, skewness, interquartile range (IQR), and outlier detection are used to identify turbulence behavior, flow instability, and friction-related pressure loss.

The results demonstrate clear evidence of:
- Turbulence transition
- Pressure drop
- Velocity fluctuations
- Nonlinear flow behavior
- Pipe friction loss caused by viscous effects

This framework provides a scalable and efficient environment for analyzing complex Navier–Stokes-based flow systems using Python.



## Run Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/belial-sys/pipe-flow-analysis.git
cd pipe-flow-analysis


#### Install Required libraries
pip install pandas numpy matplotlib seaborn

##### Prepare the Data Set
project/
└── data/
    └── simulation_dataset.csv

###### Run the Program
python main.py


####### Generated Outputs
After execution, the system will generate:

Statistical analysis results
Correlation heatmaps
Histograms and boxplots
Scatter plots
Animated pressure and velocity visualizations

Outputs will be stored inside the results/ directory.

######## Requirements
Python 3.10 or higher
Pandas
NumPy
Matplotlib
Seaborn

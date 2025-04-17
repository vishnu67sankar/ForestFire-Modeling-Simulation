# Forest Fire Modeling and Simulation

In this work a forest fire is modeled using the SEIQRDP model. The SEIQRDP model is originally used for disease transmission, and it is a 1D model. It is modified and adapted for a 2D forest fire model which is solved by a custom built RK4 method. Its implementation  can be found in the jupyter notebook. The output from the model is visualized below:

![Spatial SEIQRDP model diagram](output/fire_spread.gif)

Details of the original SEIQRDP model for disease transmission can be found in the paper below
## Citations

Wilta, F., Chong, A. L. C., Selvachandran, G., Kotecha, K., & Ding, W. (2022). Generalized Susceptible--Exposed--Infectious--Recovered model and its contributing factors for analysing the death and recovery rates of the COVID-19 pandemic. *Applied Soft Computing*, *123*, 108973. [Link to Paper](https://doi.org/10.1016/j.asoc.2022.108973)

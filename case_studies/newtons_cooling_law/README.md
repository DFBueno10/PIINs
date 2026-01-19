# Case Study: Newton's Cooling Law

## Physical problem

Newton's cooling law describes the rate at which the temperature of a body changes when it is placed in an environment with a different temperature.

## Mathematical formulation
The governing ordinary differential equation is given by:
dT/dt = -k (T - T_ext)

where:
- T(t) is the temperature of the body as a function of time,
- T_ext is the ambient temperature,
- k is the cooling constant.

## PINN formulation
In this study, a Physics-Informed Neural Network is trained to approximate the temperature evolution over time by minimizing a loss function composed of:
- the residue of the diferential equation (loss_pde);
- the initial condition error (loss_ic);
- the deviation from the data set (loss_data)


## Results
The PINN solution is compared with the analytical solution, showing good convergence even with high noise data input or without data.

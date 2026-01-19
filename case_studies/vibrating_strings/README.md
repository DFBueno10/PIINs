# Case Study: Vibrating Strings

## Physical problem
The problem is descibred by of a stretched string. The idea of the study is to sintetize a string sound with fidelity from the developed model.

In this case study, vibrating strings are used as a benchmark problem for Physics-Informed Neural Networks.

## Mathematical formulation
The motion of a vibrating string is governed by the one-dimensional wave equation:

∂²u/∂t² = c² ∂²u/∂x²

where:
- u(x, t) represents the transverse displacement of the string,
- c is the wave propagation speed.

Boundary conditions are imposed at the string ends, along with initial displacement and velocity conditions.

## PINN formulation
A Physics-Informed Neural Network is trained to approximate the spatio-temporal solution of the wave equation by minimizing a loss function composed of:
- the governing differential equation residual,
- boundary condition errors,
- initial condition errors.



## Results
The PINN solution reproduces the expected wave propagation and standing wave patterns of the vibrating string.

## Note
This case study is stil in development...


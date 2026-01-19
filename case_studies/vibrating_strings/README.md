# Case Study: Vibrating Strings

## Physical problem
The problem is descibred by of a stretched string. The idea of the study is to sintetize a string sound with fidelity from the developed model.
Diferent aproachs can be used for the problem formultation, the ends of the string may be strictly fixed, the system could dissipate energy etc. 

## PINN formulation
A Physics-Informed Neural Network is trained to approximate the spatio-temporal solution of the wave equation by minimizing a loss function composed of:
- the differential equation residue,
- boundary condition errors,
- initial condition errors
- Data erros.

## Results
The PINN was able to converge to helmholtz one dimensional solution with the help of the data set, but the process took time and required a more complex network.

## Note
This case study is stil in development...

